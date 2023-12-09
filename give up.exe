@echo off 
:1 
echo Do you really want to give up? 
set /p input= 
if /i %input%==Yes shutdown /s /t 10 & goto end
if /i %input%==no goto hope 
if /i not %input%==Yes,no echo "ERROR" & goto 1 
:end 
echo You shouldn't have done that. 
color F0 
color F1 
color B2 
color F3 
color C4 
color F5 
color F6 
goto end 
:hope 
echo It's a good choice. 
pause
exit 
