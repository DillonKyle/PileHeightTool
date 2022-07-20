# PileHeightTool
A utility to calculate the elevations and heights of piles from csv files exported from PointStudio

GUI is created using tkinter<br>
Image assets are written into main.py as base64 code and decoded, built, then deleted at every startup to prevent an installation directory<br>

To build main.py into a single file executable:<br>
* Install PyInstaller with pip:
```
pip install pyinstaller
```
* Run:
```
Pyinstaller --onefile --icon=assets/icon.ico main.py
```
