# tensorflow-tutorial
## Installation on Windows
1. [Download Winpython 3.5.2 64bit](https://sourceforge.net/projects/winpython/files/WinPython_3.5/3.5.2.3/WinPython-64bit-3.5.2.3Qt5.exe/download)
1. Install Winpython 3.5.2 : Install Direectory : `C:\WinPython-64bit-3.5.2.3Qt5`
1. `File Explorer` - `This PC` - `Property` - `Advanced system settings` - `Environment Variables`
1. Append the followings to `PATH`
    - `C:\WinPython-64bit-3.5.2.3Qt5\python-3.5.2.amd64`
    - `C:\WinPython-64bit-3.5.2.3Qt5\python-3.5.2.amd64\Scripts`
1. Reboot
1. `Windows Key` + `R` -> `powershell` -> `Enter`
1. `python --version`
1. `pip --version`
1. `pip install tensorflow`
1. Done

## Mac OS X
1. Open `Terminal`
1. `sudo easy_install pip`
1. `sudo easy_install --upgrade six`
1. `pip install tensorflow`
