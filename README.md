# wuxiaworld_export_ebook
This Python script will download chapters from novels availaible on wuxiaworld.com and saves them into the .epub format.
Based on a Fork of [Wuxiaworld-2-eBook](https://github.com/MakeYourLifeEasier/Wuxiaworld-2-eBook).

## Getting Started

To run this script you'll need to have Python >=3.4.x installed which you can find [here](https://www.python.org/downloads/ "Python Download Link").

### Features

- Download and save you favorite Novels from wuxiaworld.com into a .epub file
- Automatically adds some metadata like author, title and cover
- Customizable style whith a style editor/previewer
- Automatic update of the novel database if database file last modification >= 12h

### Prerequisites

As mentioned before this script was written for Python >=3.4.x.

Additionally the packages PyQt4, lxml and Beautifulsoup4 are required.

To install all dependencies just use the console to navigate into the project folder and write

```
pip install -r requirements.txt
```
For PyQt4 on windows use the package at this address https://www.lfd.uci.edu/~gohlke/pythonlibs/#pyqt4

#### On MacOs
1. Install ANACONDA => https://www.anaconda.com/download/#macos
2. Open a terminal
3. conda install -c anaconda pyqt=4.11.4

### Usage

Download the script and navigate to the folder using the console then write
```
python wuxiaworld_export_ebook.py
```
or just use the start.bat file. If you didn't add Python to the PATH variable during the installation or afterwards the write
```
path/where/you/installed/python.exe wuxiaworld_export_ebook.pyw
```
If you whan to start the script without database update and version check you could add the argument noupdate in your command or use the start_without_update.bat

After that just select the novel you want to read, select the output mode(classic or alternative), the book number(if applicable) and the chapters range, finaly hit the "Generate" Button.
Keep it mind that it will take some time for the script to finish, so don't close the window or the console if the program doesn't respond.

#### On Linux and MacOs
```
python3 wuxiaworld_export_ebook.pyw
```
or use the sctipt start.sh

## Keep in mind!

If you have troube with missing text in some Novels use [the legacy console application](https://github.com/MrHaCkEr/Wuxiaworld-2-eBook/tree/legacy-console-application). This script scrapes differently and could resolve problems but may need to be modified to work.

If you come across bug's or suggestion's for future updates don't hesitate to open up a "new Issue" in the issue tab

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details