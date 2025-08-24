# World Of Dreams


**World Of Dreams** is a Unreal Engine 5 project/game.

---

## Project Overview
- Developed in **UE5**.
- Simple UI/UX
- Maze
- Music
- Simple actor created in Blender
  
---
<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/962b6230-7b8b-4a77-aac7-10da8f1d2c86" />

# 3D Model Preview  

[![Model Screenshot](https://github.com/user-attachments/assets/9fb00f25-6ec4-4d18-bf1b-73d7fa1fad17)](./BLENDER/myfrogfinal.glb)  

> Click the image to open the 3D model (`.glb`) in GitHub’s built-in 3D viewer.  

---
## Running the Game
```bash
git clone git@github.com:elinakly/UE5_World_Of_Dreams.git
cd UE5_World_Of_Dreams
```

### From Unreal Editor
1. Open Worldofdreams.uproject` in UE5.
2. Press **Play** in the editor to test the game.

### Standalone Build (No UE5 Needed)
1. Download a zip file from RELEASES 
2. Right-click the ZIP file.
3. Select “Extract All…”.
4. Choose a destination folder, e.g.:
5. 
  C:\Games\UE5_World_Of_Dreams

6. Click Extract.
7. Open terminal and run
```bash
cd .\Windows\Worldofdreams\Binaries\Win64\
./Worldofdreams-Win64-Shipping.exe
```


## Git Setup
- Git is used for source control.
- `.gitignore` excludes:
- Binaries/
- DerivedDataCache/
- Intermediate/
- Saved/
- Build/

- Large UE5 assets (`.uasset`, `.umap`) are tracked via **Git LFS**.
