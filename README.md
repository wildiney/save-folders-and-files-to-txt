# FILE/DIRS TO TEXT
[![Donate](https://img.shields.io/badge/Donate-PayPal-green.svg)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=SRWLKCPSZGQTJ)

LIST FILES AND FOLDERS INSIDE THE DIR AND WRITE THE FILENAMES IN A FILE TXT OR CSV 

## SIMPLE USE
If you just want to use the features, you can copy the exec file to a folder where you want to export the filenames to a file txt or csv.

## INSTALL / RIGHT CLICK BUTTON
Save the files export-to-XXX.exe in a folder.
To add to your right click button editing the .reg files. 
Just open the .reg with your notepad and edit the line 7 with the path to the export-XXX.exe that you just saved.
After that, save and give a double click. Your system will ask for permission, just press yes or ok.

## Recompiling
If you need make changes and recompiling to you system, use PyInstaller
pyinstaller --onefile --windowed --name export-to-txt export-txt.py
pyinstaller --onefile --windowed --name export-to-csv export-csv.py

## Donation
[![paypal](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=SRWLKCPSZGQTJ)
