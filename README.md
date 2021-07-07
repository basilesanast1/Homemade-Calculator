# Homemade-Calculator
I created my calculator in Batch script

If you want to create it too:

1. Open Notepad ++

2. Paste this code:
@echo off

setlocal EnableDelayedExpansion

mode 30,10

:calc

cls

echo Add = +

echo Subtract = -

echo Divide = /

echo Multiply = *

echo Put your question here:

set /p equ=

set /a equ=!equ!

cls

echo Answer:!equ!

pause
goto calc

3. Save as .bat


Enjoy!
