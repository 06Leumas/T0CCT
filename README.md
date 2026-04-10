# T0CCT - Tricking 0 Clothing Customizer Tool
### What is T0CCT?
T0CCT (Tricking 0 Clothing Customizer Tool) is a tool made for adding custom clothing textures into Tricking 0. Ive figured out how to mod the game manualy, and now I wanna share a way to do it quick and easy! In this document, you will learn how the tool works, how to use the app and last but for sure not least, how to make your own custom clothing textures!

### Quick Download
Use the this link to download the latest version of T0CCL:

- `Nightly Download`: https://github.com/06Leumas/T0CCT/releases/download/nightly/T0CCT-windows.zip
- Do not use GitHub's **Code -> Download ZIP** for the app. That downloads the repository source archive, not the proper packaged app download.

### How does it work?
This tool works by extracting the .asset file/folder that the clothes are saved in ingame, replacing the texture with your new customized texture, and then repacking the .asset file with your your new customized texture for the clothing piece.



---

## How to Download and Use

1. **Check the Required Files**
   - Make sure `T0CCT.exe`, `texture_mapping.json`, and `classdata.tpk` are in the same folder.

2. **Open the Tool**
   - Run `T0CCT.exe`.

3. **Set Your Game Path**
   - Click the settings icon in the top-left corner.
   - If the tool finds your game automatically, your good to go and can continue to step 4!
   - If not, paste your Tricking 0 folder path or click **Browse...**.
   - Example path:
     ```
     C:\Program Files (x86)\Steam\steamapps\common\Tricking 0
     ```

4. **Choose a Clothing Option**
   - Click on the clothing option you want to replace.

5. **Import Your PNG**
   - Drag and drop your PNG into the app,
   - or click **Browse PNG** to choose it manually in your file system.

6. **Apply the Texture**
   - Click **Apply To Game**.

7. **Enjoy!**

---
## How to make your own Clothing texture
Follow the different tutorials ive made on editing the different textures, as the process can depend on the type of clothing your trying to edit. I recommend starting with this general tutorial i made that will teach the the principles. These the tutorials ive made so far:
   - T0CCT: How to customize a clothing piece (The principles).
   - T0CCT: How to customize Shorts

---
## Other info:

## How to Find the Tricking 0 Folder

1. Open Steam.
2. Right-click **Tricking 0** in your Library.
3. Click **Manage**.
4. Click **Browse local files**.
5. File Explorer will open your Tricking 0 install folder.
6. Copy that folder path and paste it into T0CCT Settings.


## Backup and Restore

- The tool creates a one-time backup called `resources.assets.original` inside your `TRICKING_0_Data` folder.
- If you want to restore the original clothing texture:
  - delete the modified `resources.assets`
  - rename `resources.assets.original` back to `resources.assets`


## Important Notes

- Keep `T0CCT.exe`, `texture_mapping.json`, and `classdata.tpk` in the same folder.
- This tool edits the:
  ```
  TRICKING_0_Data\resources.assets
  ```
  texture.
- Make sure the file you replace the texture with is a .png.
- Support for other clothes is planned, but not finished quite yet..

---
If you run into issues, feel free to DM me (@06leumas) on Discord and I'll gladly try to help!
