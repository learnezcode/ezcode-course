# ezcode
@csoftware

## Как написать свой курс для ezcode

ezcode использует формат yaml для хранения параметров курса

Для наилучшей точности курс лучше писать на **английском** языке

CoGen AI читает название и описание. Для CoGen AI описание - инструкция, которой он следует для написания

В курсе учитывается название и описание

Пример yaml файла официального курса по Python

```yaml
name: Python. Start to code
description: Do you want to learn Python? You are on the right track! Python is the best language in the world (real)
course:
  1:
    chapter-name: Hello World
    info: In this chapter you need to describe how to install on windows/linux (use linux mint as example on linux), first 'hello world' code and what it means. Describe about comments. Next chapter is 'Types of variables'
  2:
    chapter-name: Types of variables
    info: In this chapter you need to describe types of variables, like str, int, etc. Tell about f-string on python when you describe strings. Use code examples. Describe how to work with all types of variables on code. List, tuples, strings, float and int. Describe about f-strings and examples like '2+2' after you describe int and what you can do with int (+,-,*,/,//,%). Next chapter is how input and output works with examples
  3:
    chapter-name: Greetable input and output
    info: In this chapter you need to describe how to use input string and print content and create basic Hello Name program.  Next chapter is Functions
```

### Поясенния

- name - имя курса (высвечивается на главной)
- description - описание (встречается на главной)
- course - содержание курса (CoGen AI на 100% учитывает содержимое курса)
- - цифра - глава курса
- - - chapter-name - имя главы (по ней CoGen AI строит минимальную картину курса)
- - - info - описание главы (CoGen AI по ней строит всю главу, поэтому здесь расписываем подробнее некуда)

если появляется какой-то лишний параметр - CoGen AI не учитывает это

### Мануал который стоит прочитать перед написанием курса

https://platform.openai.com/docs/guides/prompt-engineering

Он очень подробно описывает как правильно составлять запрос для ИИ (в частности gpt4-omni)
