@echo off

echo PC Cleaner by th3hash, Cleaning system junk files, please wait…
REM displays a line of text

del /f /s /q %systemdrive%\*.tmp
del /f /s /q %systemdrive%\*._mp
del /f /s /q %systemdrive%\*.log
del /f /s /q %systemdrive%\*.gid
del /f /s /q %systemdrive%\*.chk
del /f /s /q %systemdrive%\*.old
del /f /s /q %systemdrive%\recycled\*.*
del /f /s /q %windir%\*.bak
del /f /s /q %windir%\prefetch\*.*
rd /s /q %windir%\temp & md %windir%\temp
del /f /q %userprofile%\cookies\*.*
del /f /q %userprofile%\recent\*.*
del /f /s /q “%userprofile%\Local Settings\Temporary Internet Files\*.*”
del /f /s /q “%userprofile%\Local Settings\Temp\*.*”
del /f /s /q “%userprofile%\recent\*.*”

REM /f: force deleting of read-only files
REM /s: Delete specified files from all subdirectories.
REM /q: Quiet mode, do not ask if ok to delete on global wildcard
REM %systemdrive%: drive upon which the system folder was placed
REM %windir%: a regular variable and is defined in the variable store as %SystemRoot%. 
REM %userprofile%: variable to find the directory structure owned by the user running the process

echo Cleaning of junk files is finished!
REM displays a line of text

echo. & pause
REM echo.: Displays a single blank line on the screen.
REM pause: This will stop execution of the batch file until someone presses "any key"
