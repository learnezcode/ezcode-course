# ezcode @csoftware ## Kak napisat' svoy kurs dlya ezcode ezcode ispol'zuyet format yaml dlya khraneniya parametrov kursa Dlya nailuchshey tochnosti kurs luchshe pisat' na **angliyskom** yazyke CoGen AI chitayet nazvaniye i opisaniye glavy. Dlya CoGen AI opisaniye glavy - instruktsiya, kotoroy on sleduyet dlya napisaniya V kurse uchityvayetsya nazvaniye i opisaniye Primer yaml fayla ofitsial'nogo kursa po Python ```yaml name: Python. Start to code description: Do you want to learn Python? You are on the right track! Python is the best language in the world (real) course: 1: chapter-name: Hello World info: In this chapter you need to describe how to install on windows/linux (use linux mint as example on linux), first 'hello world' code and what it means. Describe about comments. Next chapter is 'Types of variables' 2: chapter-name: Types of variables info: In this chapter you need to describe types of variables, like str, int, etc. Tell about f-string on python when you describe strings. Use code examples. Describe how to work with all types of variables on code. List, tuples, strings, float and int. Describe about f-strings and examples like '2+2' after you describe int and what you can do with int (+,-,*,/,//,%). Next chapter is how input and output works with examples 3: chapter-name: Greetable input and output info: In this chapter you need to describe how to use input string and print content and create basic Hello Name program. Next chapter is Functions ``` ### Poyasenniya - name - imya kursa (vysvechivayetsya na glavnoy) - description - opisaniye (vstrechayetsya na glavnoy) - course - soderzhaniye kursa (CoGen AI na 100% uchityvayet soderzhimoye kursa) - - tsifra - glava kursa - - - chapter-name - imya glavy (po ney CoGen AI stroit minimal'nuyu kartinu kursa) - - - info - opisaniye glavy (CoGen AI po ney stroit vsyu glavu, poetomu zdes' raspisyvayem podrobneye nekuda) yesli poyavlyayetsya kakoy-to lishniy parametr - CoGen AI ne uchityvayet eto ### Manual kotoryy stoit prochitat' pered napisaniyem kursa https://platform.openai.com/docs/guides/prompt-engineering On ochen' podrobno opisyvayet kak pravil'no sostavlyat' zapros dlya II (v chastnosti gpt4-omni)
Ещё
2 176 / 5 000
# ezcode
@csoftware

## How to write your own course for ezcode

ezcode uses the yaml format to store course parameters

For best accuracy, it is better to write the course in **English**

CoGen AI reads the title and description of the chapter. For CoGen AI, the chapter description is the instruction it follows to write

The course takes into account the title and description

Example of the official Python course yaml file

```yaml
name: Python. Start to code
description: Do you want to learn Python? You are on the right track! Python is the best language in the world (real)
course:
1:
chapter-name: Hello World
info: In this chapter you need to describe how to install on windows/linux (use linux mint as example on linux), first 'hello world' code and what it means. Describe about comments. Next chapter is 'Types of variables' 2: chapter-name: Types of variables info: In this chapter you need to describe types of variables, like str, int, etc. Tell about f-string on python when you describe strings. Use code examples. Describe how to work with all types of variables on code. List, tuples, strings, float and int. Describe about f-strings and examples like '2+2' after you describe int and what you can do with int (+,-,*,/,//,%). Next chapter is how input and output works with examples 3: chapter-name: Greetable input and output info: In this chapter you need to describe how to use input string and print content and create basic Hello Name program. Next chapter is Functions
```

### Explanations

- name - course name (displayed on the main page)
- description - description (found on the main page)
- course - course content (CoGen AI takes course content into account 100%)
- - number - course chapter
- - - chapter-name - chapter name (CoGen AI builds a minimal picture of the course based on it)
- - - info - chapter description (CoGen AI builds the entire chapter based on it, so there is no room for more detail here)

if any extra parameter appears, CoGen AI does not take it into account

### Manual that is worth reading before writing a course

https://platform.openai.com/docs/guides/prompt-engineering

It describes in great detail how to correctly compose a request for AI (in particular gpt4-omni)
