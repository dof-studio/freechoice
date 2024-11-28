# freechoice
Free financial data now! Use automatic downloader to download Choice data. For research use only~

# Choice version
We personally recommend to use `6.x` versions. We strongly recommend to replace the resources of screenshots of buttons by the one shown on your device.

# We provide a free Excel bypassing tool
Always opening an excel when files are saved? Let's use `EmptyPP.exe` to trick it!
```text
Idea: Because the Choice terminal will call the program to open xlsx by default to open the
      downloaded file after downloading the data, we only need to use an empty program and
      set it as the default program to open xlsx to avoid the problem of slow automatic download
      speed caused by the need to open the data file.
Contributor: fliggy39
```

# We provide free data pre-processing tools
We provide a `R` processing tools that can automatically clear and sort the data.

We also provide a `MySQL` tool written in `Python` to automatically archive your data into your own database.
```text
Idea: Why not saving your data into a Rds or SQL file so you can easiyly retrieve the part
      you need next time?
Contributor: dof-studio
```

# How to use it
1. Set up the Python environment and install the following dependency.
```text
xlrd
shutil 
datetime
pyautogui
pyperclip
```

2. Clone our repository.
```bash
git clone https://github.com/dof-studio/freechoice
```

3. Extract `src`, `res`, `utils` folders and merge all files into one single folder, which contains all of the:
```text
i)   resources files with suffix '*.png'
ii)  source code files with suffix '*.py'
iii) utility tools with suffix '*.cpp', '*.py', '*.exe'
```

4. [Optional] Do your screenshots and replace all of the resource files by your Choice UI.
```text
Refer to res\resource_list\list.csv to see what screenshots do we use
```

5. Run the main `.bat` file to start
```bash
cmd freechoice.bat
```

# Future TODO
```text
Just like you all. 
I am tired of writing `code` in Excel like this script.
DOF Studio and my partner are working on developping an assembly-like srcipt language that can replace the tedious Excel programming.
Maybe Next version.
```

# Happy to see bug reports
We admit that EastMoney is continuously improving, in terms of trying to avoid us to use automatic tools to fetch data, their product. If you see this does not work on your computer becase of `UI update`, `logic update`, `more anti-autopygui enhancement`, and so, welcome to report a bug by opening an `issue`. 


Let's fight for freechoice!
