# Blocking-Windows-10-Forced-Updates
Windows Updates can be a pain especially when you have a limited data plan. 
#Go to your Start Up Folder Win + R
# Type shell:Startup Enter
#Create a new batch file and add this code to the batch file
# Use a text editor probably notepad ++ works for me
# batch files are saved with the .bat extension
# So here is the code
:a
killprocess Windows10UpgraderApp.exe
timeout 10
goto a

# Just save file to yours start up folder
# All this may need Adminstrator rights, grant access
and that is it.
