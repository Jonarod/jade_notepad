jade_notepad
============

Notepad++ Jade syntax highlighter


##Overview
Jade is a templating language used in Node.js to render html in a simple and beautiful way. 
Learn more on Jade on the [Official Github](https://github.com/visionmedia/jade/) and some very cool learning websites [here](http://www.learnjade.com/), [here](http://jade-lang.com/) and [here](http://naltatis.github.io/jade-syntax-docs/).

Jade_notepad extends Notepad++ standard language library to highlight specific syntax of jade in order to visually beautify your code.
Do not waste you time to scan you code anymore : picture it!!

##Features

* Jade specific syntax in dark orange.
* Html syntax with default Notepad++ html color codes.
* Comments greened out just like in other default Notepad++ languages.
* Data bindings such as `#{data}` are highlighted specifically to be eye-catching.


##Install

### By importing
1. Download the UserDefineLang.xml file to your computer.
2. Open NotePad++.
3. Go to `Language` then `User-Defined`.
4. On the new window click `Create New...` and enter `Jade` and press `Ok`.
5. Click on `Import...` and select the file you just downloaded.
6. Click on `Save as...` and you are done!


### By copy/paste
1. Download the UserDefineLang.xml file to your computer.
2. Go to your local Notepad++ appdata directory, usually located in :
`C:\Users\YourUserName\AppData\Roaming\Notepad++`
You can also do Windows+R to open the run command and type in : `%APPDATA%\Notepad++`
4. If this is the first userdefined language you are adding, 
   just replace the UserDefineLang.xml by the one you just downloaded. 
   If this is the second or more language you add, 
   simply copy everything from the first file starting at `<UserLang...>` 
   to `</UserLang>` and paste it at the end of the userDefineLang.xml right 
   before `</NotepadPlus>`
6. Save the newly improved userDefineLang.xml.

##Known issues to be resolved

* css like syntax is not correctly highlighted if it starts by an html tag e.g `div#Id.MyClass` do not work properly but `div(id="Id", class="MyClass")` or `#Id.MyClass` will work.
* Quotes are not escaped.

##To Do

* Highlight specific client side template syntaxes like Angular.js.
* Specific folding behavior (hide/show): e.g folding an entire html node to reduce size of visible code.
