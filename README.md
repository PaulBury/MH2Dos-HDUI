# MH2Dos-HDUI

A fan-made 2x, 4, 8x, and 16x high-resolution UI texture pack for Monster Hunter 2 Dos By PaulBury. Made for use in the PSCX2 emulator alongside the English Patch and MH2Plus deltaX patches.
Tries to fix various issues with the original UI.

Work in Progress, updates will be slow.  

### [Installation + Download](https://github.com/PaulBury/MH2Dos-HDUI/tree/main?tab=readme-ov-file#download-and-install)  

Inspired by the excellent [MH4HDUI Project by xl3lackout](https://github.com/xl3lackout/MH4HDUI).


Created from scratch using Inkscape 1.4, Affinity Designer/Photo 2.5.5, Blender, and Substance Designer 2022. Source files are available for exporting at high-res.
Inspired by multiple Monster Hunter art books and other resources, I aimed to match the original in-game textures as closely as possible.  
However, in some cases, I took artistic liberty or had insufficient references.  

I probably won't accept pulls for the project. If you create a fork of my work, please credit me.  

Feedback and suggestions for the project are welcome! You can create an issue on Github, ping me on Discord servers I'm active in, or message me directly on Discord (username paulbury).  

### Progress
-----------------------------------------------------------------------------------------------------------
80% ---- INGAME HUD        

80% ---- ICONS             

20% -- MENU UI ELEMENTS 

0% -- MAPS             

0% -- BACKGROUNDS      

60% --- LOADING SCREEN    


0-75%  =  Work in Progress, parts might be low res.  
80-90% =  Completely usable, but not fully based on the original textures and can be improved.  
100%   =  Fully finished; it should closely resemble the original game texture at the same resolution.


Fonts might never get upscaled, as PCSX2 generates font textures on the go in MH2Dos. (9000+ files)


Planned variants:  
21:9  
Semi-transparent (mainly for maps when they are done etc.)  


If somebody teaches me how to patch in textures or PCSX2 adopts how custom textures work like in other emulators, I will update the project accordingly.


### DOWNLOAD AND INSTALL
-----------------------------------------------------------------------------------------------------------  
To download source files, click the green "Code" button at the top of the page and select "Download ZIP."
![DownloadSOURCE](https://github.com/user-attachments/assets/e48b1014-46a3-4ccf-9c82-97baea001c7c)

To download ready-to-use files, click on ["Releases"](https://github.com/PaulBury/MH2Dos-HDUI/releases/latest) on the right side of the page and download the parts and variants of the pack you want. Various sizes are available.  
Extract with 7-Zip.

### IMPORTANT
PCSX2 loads custom textures from memory! Many textures get generated in Monster Hunter 2 Dos. That's why some parts of the pack are large.  
SOME TEXTURES MIGHT NOT WORK ALL THE TIME:  
Item_icons folder (generated textures)  
LoadingScreen_Kushala folder (generated textures)  

To fix this issue, more textures must be dumped, more in the "How can I help" section. 

#### "What do I download?"
-----------------------------------------------------------------------------------------------------------  
The pack is separated into multiple sizes and part variants.  

File names are constructed like:  
MH2DosHDUI_VERSION_RATIO_SIZE_VARIANT.7z  
**.7z compression reduces the size from 500MB (16x version) to about 10MB.**  

2x, 4x, 8x, and 16x refer to how many times bigger the textures are compared to the original 256x256 resolution.  
4-3 and 16-9 are aspect ratios, 4-3 is the original and 16-9 is for use with a widescreen patch/hack.  
Future variants (e.g. semi-transparent maps) will need to be downloaded separately, overwriting the files in the standard pack.  

Examples of what each category/folder affects:  
HUD (recommended, has no duplicates)  
![HUD](https://github.com/user-attachments/assets/e9a07a86-3f01-4f8d-b95d-f9363ebde119)  

ItemIcons (recommended, but contains duplicates)  
![ItemIcons_small](https://github.com/user-attachments/assets/25391864-f3d4-4ec3-ab5e-a2e0eb8407ec)  

LoadingScreenBorder (recommended, has no duplicates)  
![Border_small](https://github.com/user-attachments/assets/f3675126-0a5f-4423-8daa-31bb8805d7e7)  

LoadingScreenKushala (up to preference, contains duplicates)  
![LoadingScreenKushala_small](https://github.com/user-attachments/assets/612fe723-e547-49f1-964e-cf9007ac6b14)  

UIElements (recommended, has no duplicates)  
![UIElements](https://github.com/user-attachments/assets/a50f2a42-29b9-4670-b817-cb603c0e67e9)  

### Installation (PCSX2):  
-----------------------------------------------------------------------------------------------------------  

1. Check MH2's Serial Number. Right-click on the game's entry in the emulator -> Game Properties -> Serial Number, it should be SLPM-66280. Remember this name.

![Step1](https://github.com/user-attachments/assets/621e7f77-c682-4e3b-95ae-57920548b4a7)

2. Go to Settings -> Graphics -> Texture Replacement and enable Load Textures (to enable custom textures for MH2 only, right-click on the game's entry in the emulator and click Game Properties)


3. Check the correct folder for custom textures under Settings -> Graphics -> Texture Replacement -> Search Directory

![Steps2and3](https://github.com/user-attachments/assets/727cf02a-395a-466e-bcc9-e03e0478be28)

4. Extract the downloaded .zip pack variants into PCSX2/textures/(MH2's Serial Number)/replacements. (it should be SLPM-66280) You might need to launch the game first or create both folders manually in PCSX2/Textures using your game's Serial Number as the folder name.

![Step4](https://github.com/user-attachments/assets/dfd93e32-69a4-4c96-8266-ec73551877be)


**If you're using other texture packs, do not extract the folders. Instead, replace existing texture pack files with this project's files from the categorized folders.**


Instructions for Mobile will be added in the future. (if custom textures even work on Mobile)

### How can I help?
-----------------------------------------------------------------------------------------------------------
Turn on "Dump Textures" in MH2Dos' Game Properties, play, and then check the textures get dumped in the location from the pictures above, in a folder named "dumps" instead of replacements.  
As you play MH2Dos, PCSX2 will gradually dump textures. You can contact me on discord (nickname: paulbury), and I will tell you what file names I need.  

![OptionalStep](https://github.com/user-attachments/assets/63786923-a416-4826-ad3b-38c0955dfd5a)

### Gallery
-----------------------------------------------------------------------------------------------------------  


### Credits
-----------------------------------------------------------------------------------------------------------
[Monster Hunter Font](https://www.deviantart.com/xmitsarugix/art/Monster-Hunter-Font-Type-1-and-2-380816151) by [Mitsarugi](https://monsterhunter.fandom.com/wiki/User:Mitsarugi)  
[Zugzwang](https://x.com/ZugzwangMH) for providing references.  
Dark_Knight for help.  

Textures:  
[Gray and White Concrete Wall](https://unsplash.com/photos/gray-and-white-concrete-wall-ug3EcRGb3I8) by Annie Spratt on Unsplash  
[a rusted metal surface with lots of rust on it](https://unsplash.com/photos/a-rusted-metal-surface-with-lots-of-rust-on-it-FmeJ2pV6YsU) by takis politis on Unsplash  


### LICENSE
-----------------------------------------------------------------------------------------------------------
This work's SOURCE files are licensed under a [CC BY-NC-SA 4.0][cc-by-nc-sa].  
BY: Credit must be given to me, the creator.  
NC: Only noncommercial use of this work is permitted.  
SA: Adaptations must be shared under the same terms.  
[![CC BY-NC-SA 4.0][cc-by-nc-sa-shield]][cc-by-nc-sa]  

[![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa]  

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/  
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png  
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg  

Based on original work by Capcom.  


### OTHER
-----------------------------------------------------------------------------------------------------------
I apologize to anyone who tries to make sense of the source files. Make sure to use Inkscape's Layers and Objects tab. 
Also, it's my first time using Github, so mistakes will be made.  

Bulk Rename Utility with Import Rename-Pairs feature was used to rename all the files. Source files include filelist_(name).txt with all texture names using the image.  
