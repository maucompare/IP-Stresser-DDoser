title IP Rainbow Pinger - Made by Maussist
echo off & cls
color c

echo               ...                                
echo              ;::::;                              
echo            ;::::; :;                              
echo          ;:::::'   :;                             
echo         ;:::::;     ;.                           
echo        ,:::::'       ;           OOO\           
echo        ::::::;       ;          OOOOO\            
echo        ;:::::;       ;         OOOOOOOO           
echo       ,;::::::;     ;'         / OOOOOOO          
echo     ;:::::::::`. ,,,;.        /  / OOOOOOO        
echo   .';:::::::::::::::::;,     /  /     OOOOO     
echo  ,::::::;::::::;;;;::::;,   /  /        OOOO     
echo ;::::::'::::::;;;::::: ,#/  /          OOOO   
echo ::::::::;::::::;;::: ;::#  /            OOOO   
echo ::::::::;:::::::: ;::::# /              OOO   
echo `:`:::::::`;:::::: ;::::::#/               OOO
echo  :::`:::::::;; ;:::::::::##                OO
echo  ::::`:::::::;::::::::;:::#                OO
echo  `:::::`::::::::::::;':;::#                O
echo   `:::::`::::::::;' /  / :#
echo    ::::::`:::::;'  /  /   #                                                                                                                                 
set /p IP=Enter the niggers IP :
echo.
:rainbow
PING -n 1 %IP% | FIND "TTL="
IF ERRORLEVEL 1 (SET in=c & echo %IP%  Sending Bytes=32 )
ping -t 2 0 10 127.0.0.1 >nul
color 01
PING -n 1 %IP% | FIND "TTL="
IF ERRORLEVEL 1 (SET in=c & echo %IP%  Sending Bytes=32  )
ping -t 2 0 10 127.0.0.1 >nul
color 02
PING -n 1 %IP% | FIND "TTL="
IF ERRORLEVEL 1 (SET in=c & echo %IP%  Sending Bytes=32 )
color 3PING -n 1 %IP% | FIND "TTL="
IF ERRORLEVEL 1 (SET in=c & echo %IP%  Sending Bytes=32 )
color 4
PING -n 1 %IP% | FIND "TTL="
IF ERRORLEVEL 1 (SET in=c & echo %IP%  Sending Bytes=32 )
color 5
PING -n 1 %IP% | FIND "TTL="
IF ERRORLEVEL 1 (SET in=c & echo %IP%  Sending Bytes=32 )
color 6
PING -n 1 %IP% | FIND "TTL="
IF ERRORLEVEL 1 (SET in=c & echo %IP%  Sending Bytes=32 )
color 7
PING -n 1 %IP% | FIND "TTL="
IF ERRORLEVEL 1 (SET in=c & echo %IP%  Sending Bytes=32 )
color 8
PING -n 1 %IP% | FIND "TTL="
IF ERRORLEVEL 1 (SET in=c & echo %IP%  Sending Bytes=32 )
color 9
PING -n 1 %IP% | FIND "TTL="
IF ERRORLEVEL 1 (SET in=c & echo %IP%  Sending Bytes=32 )
color 0b
PING -n 1 %IP% | FIND "TTL="
IF ERRORLEVEL 1 (SET in=c & echo %IP%  Sending Bytes=32 )
color 0c
PING -n 1 %IP% | FIND "TTL="
IF ERRORLEVEL 1 (SET in=c & echo %IP%  Sending Bytes=32 )
color 0d
PING -n 1 %IP% | FIND "TTL="
IF ERRORLEVEL 1 (SET in=c & echo %IP%  Sending Bytes=32 )
color 0e
PING -n 1 %IP% | FIND "TTL="
IF ERRORLEVEL 1 (SET in=c & echo %IP%  Sending Bytes=32 )
color 0f
PING -n 1 %IP% | FIND "TTL="
IF ERRORLEVEL 1 (SET in=c & echo %IP%  Sending Bytes=32 )
ping -t 2 0 10 127.0.0.1 >nul
goto rainbow