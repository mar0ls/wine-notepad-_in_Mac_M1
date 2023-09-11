# HOW INSTALL NOTEPAD++ IN MAC M1.


# **1. Install homebrew:**
    /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"


# **2. Execute command in the terminal to install Wine:**
    brew install –no-quarantine gcenx/wine/wine-crossover
<img width="872" alt="wine" src="https://github.com/mar0ls/wine-notepad-_in_Mac_M1/assets/120790937/1b8f7419-488b-4def-aa6a-2d75636ec0b0">


# **3. [OPTIONAL] execute the command in the terminal and you can check the version of the program or change the default operating system version.**
    wine winecfg
   
# **5. Download Notepad++**
[Link to notepad 8.5.6](https://github.com/notepad-plus-plus/notepad-plus-plus/releases/download/v8.5.6/npp.8.5.6.Installer.x64.exe)

# **6. Double-click the setup file and then allow Wine to access the folder.**
<img width="566" alt="npp" src="https://github.com/mar0ls/wine-notepad-_in_Mac_M1/assets/120790937/58eac64b-f44c-46ed-b19e-f14d71a27609">

   
# **8. That's all. If you want to run the Windows program again on your PC later, open the terminal and execute the  command.**
    wine start notepad++.exe or wine64 notepad++.exe

