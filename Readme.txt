codeblock qt4 windows

資料來源: https://blog.csdn.net/soundwave_/article/details/53149544
https://download.qt.io/archive/qt/4.8/4.8.5/
https://pilotfiber.dl.sourceforge.net/project/nasame2013/sources/MinGW-gcc440_1.zip

01.安裝CB
02.解開MinGW並替換CB對應資料夾
03.安裝QT
04.測試CB產生QT專案
	codeblocks qt console window[ https://forums.codeblocks.org/index.php?topic=8942.0 ]
		Ahh I've got it sorted by changing the build options of the project to a GUI application. Project->Properties->Build Targets, change "Console Application" to "GUI Application".
	
	
	