# cpp-spielplan
 Software zur Verwaltung der Ergebnisse der Fussball-Bundesliga in Deutschland 

Compiler, Framework:
Dev-Cpp 5.7.1 mit MinGW 4.8.1 ( https://sourceforge.net/projects/orwelldevcpp/ - "Dev-Cpp 5.7.1 MinGW 4.8.1 Setup.exe" ) und QT 4.8.6.1 ( https://www.qt.io/download/ - "qt-opensource-windows-x86-mingw482-4.8.6-1.exe" )
freecommandLinetools.exe

Die Projektdatei "sp.ui" für den GUI-Designer "QT Designer", das QMake-Makefile und main.cpp befindet sich im Projekt im Verzeichnis "src\framework\qt".

Der Pfad zu zum QT-bin Verzeichnis ( z.B. "C:\Qt\4.8.6\bin" ) und zum MinGW-bin Verzeichnis ( z.B. "C:\Qt\4.8.6\bin;C:\int\w32\develop\Dev-Cpp\MinGW32\bin" müssen im System-Pfad eingetragen sein.

MingGW unter Dev-Cpp benötigt die folgende Include-Verzeichnisse in den Projekteinstellungen:
-I"c:\Qt\4.8.6\include\QtCore" -I"c:\Qt\4.8.6\include\QtGui" -I"c:\Qt\4.8.6\include" -I"c:\Qt\4.8.6\include\ActiveQt" -I"c:\Qt\4.8.6\mkspecs\default" -

