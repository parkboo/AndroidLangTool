AndroidLangTool
===============

Simple tool to export android strings resourses to excel and import them to project after translating.
It will scan android project and export all strings.xml to excel file. So you will have simple way to prepare translations 

The app supports xml comments. 
missed traslations will have red backforund in xls file.

To run application execute: `java -jar LangTool.jar`

Tool has two commands: export to xls and import from xls file
 
`
export: -e <project dir> <output file>
`

**project dir** - path to android project. 

**output file** - name of excel file


`
import: -i <input file>
`

**input file** - name of excel file for importing to project 

link to binary: http://goo.gl/5EaOg

link to eclipse plugin: http://goo.gl/fwEkU


#Modified (Aug 4, 2014)
Can handle <i>&lt;string-array&gt;</i> and <i>formatted="xxx"</i>

#For Korean Users
strings.xml을 excel 문서(.xls)로 export하고 excel 문서에서 다시 strings.xml을 생성하는 툴입니다.
original 소스에 string-array 처리 기능을 추가했습니다. 
