## Blender <> Moi3D connector

### Bridge between [Blender](https://www.blender.org/download/) and [Moi3D](http://moi3d.com/):
![BMOI BANNER](https://i.imgur.com/sjLP3k8.jpg)

### System requirements:
1. Windows 10
2. Windows 10 temp folder location must be by default

### Download:
[BMOI_Connector-master.zip](https://github.com/TitusLVR/BMOI_Connector/archive/master.zip)

### Installation through download:
1. Download "BMOI_Connector-master.zip"
2. Extract somewhere
3. Install Blender addon: Move  "BMOI_Connector" folder to "C:\Users\<username>\AppData\Roaming\Blender Foundation\Blender\<Blender Version>\scripts\addons"
4. Install Moi3D scripts: open "MOI3D" folder and move its content ("Commands" and "Startup" folders) to "c:\Users\<username>\AppData\Roaming\Moi\"


### Configuration:
1. Activate the Blender addon: Run Blender > Edit > Preferences > Addons > And activate "BMOI Connector".
2. Open the moi.ini file in C: \ Users \ Your UserName \ AppData \ ROAMING \ MOI, and change the "fbx = 2010" to "FBX = 2016".


### How-to:
#### Blender:
1. Navigate or open side bar (default button "N")
2. Open BMOI3D tab
* If you want to send objects to Moi3d  - press "Send to Moi3d" button
* If you want to get result from Moi3d  - press "Get from Moi3d" button



### Moi3D:
* If you want to send objects to Blender - "BMOI Export" button (or you can add "bmoi_export_FBX" command to a hotkey)
* If you want to get objects from Blender - "BMOI Import" button (or you can add "bmoi_Import_OBJ" command to a hotkey)

Thank you!
 
