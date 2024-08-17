# APK-Info
A tool for viewing detailed info on an APK file.

Apperantly, this program has been forked, and modified a LOT of times. See the original README for the list of evolution of this program.
## Screenshot
![image](https://github.com/user-attachments/assets/dab808c8-cf05-4fa5-bfe4-869e1c8f4cce)

(no actual dark mode, sorry. it's just a theme for my OS)

# Features

Allows viewing for...
- App icon
- Package name
- Name (in all languages)
- Version
- Build number
- The minimum, maximum, and target version of the SDK (Android)
- Supported density (DPI) and screen size
- Architecture (ABI)
- Supported textures
- Permissions
- Features
- Signature
- OpenGL ES version
- Whether app supports Android TV, Wear OS, and/or Android Auto
- Locales
- A variety of hashes (MD2, MD4, MD5, SHA1, SHA256, SHA384, SHA512)
- And a lot more!

Other than that, you can also...
- Search the APK in either the Google Play Store, or APKMirror!
- Scan the APK using VirusTotal!
- Rename the apk to a more coherent name!
- Install or Uninstall the opened APK file from a device or emulator connected thru ADB!
- Add the program to the WIndows Shell for convinience!
- Drag 'n' dropping!
- Use the program in 86 different languages!

You can modify the `APK-Info.ini` file to change the language, define a pattern for renaming the APK, adding a new Android SDK level, and more!

# SDK levels support:
APK-Info supports ANY APKs ranging from the first ever Android version (API 1) all the way up to the latest (API 35)!
Here's the list of it:
```
SDK 1 = 1.0 (Base)
SDK 2 = 1.1 (Base 1.1)
SDK 3 = 1.5 (Cupcake)
SDK 4 = 1.6 (Donut)
SDK 5 = 2.0 (Eclair)
SDK 6 = 2.0.1 (Eclair 0.1)
SDK 7 = 2.1 (Eclair MR1)
SDK 8 = 2.2 (Froyo)
SDK 9 = 2.3 (Gingerbread)
SDK 10 = 2.3.3 (Gingerbread MR1)
SDK 11 = 3.0 (Honeycomb)
SDK 12 =  3.1 (Honeycomb MR1)
SDK 13 = 3.2 (Honeycomb MR2)
SDK 14 = 4.0 (Ice Cream Sandwich)
SDK 15 = 4.0.3 (Ice Cream Sandwich MR1)
SDK 16 = 4.1 (Jelly Bean)
SDK 17 = 4.2 (Jelly Bean MR1)
SDK 18 = 4.3 (Jelly Bean MR2)
SDK 19 = 4.4 (KitKat)
SDK 20 = 4.4W (KitKat Watch)
SDK 21 = 5.0 (Lollipop)
SDK 22 = 5.1 (Lollipop MR1)
SDK 23 = 6.0 (Marshmallow)
SDK 24 = 7.0 (Nougat)
SDK 25 = 7.1 (Nougat MR1)
SDK 26 = 8.0 (Oreo)
SDK 27 = 8.1 (Oreo MR1)
SDK 28 = 9.0 (Pie)
SDK 29 = 10 (Q/Quince Tart)
SDK 30 = 11 (R/Red Velvet Cake)
SDK 31 = 12 (S/Snow Cone)
SDK 32 = 12L (Sv2/Snow Cone v2)
SDK 33 = 13 (T/Tiramisu)
SDK 34 = 15 (Upside Down Cake)
SDK 35 = 16 (Vanilla Ice Cream)
```

# Compiling
To compile this program, you need AutoIt3 and SciTE4AutoIt3 installed on your computer. This is required, or else you won't be able to compile it (duh).

There are 2 ways to compile this program that I know of. Personally, I use Visual Studio Code, but you can use the SciTE editor if you want to.

Firstly, download the or clone the source code. Put it somewhere in your computer.
The entire source code is the `APK-Info.au3` file inside the `Application-source` folder

## If you're using SciTE4AutoIt3:
Simply open up the `.au3` file in the SciTE editor, make your own changes, and press `F7` or `Ctrl-F7` > `Compile Script` to compile!

However, for some reason, the program seems to output a wrong command when compiling (at least, on my end). I recommend using VSCode if you run into this problem.

## If you're using Visual Studio Code:
You need to do some extra setup to be able to compile the program under VSCode. You still need both AutoIt3 and SciTE4AutoIt3 though.

1. Install [this extension](https://marketplace.visualstudio.com/items?itemName=Damien.autoit) from the Visual Studio Marketplace. It should open up Visual Studio Code.
2. Go to the Extension Settings by clicking on the gear icon > Extension Settings
3. You only need to specify the `Ai Path` to your AutoIt3 executable, since it takes your `Ai Path` as the relative of the rest of the programs. If you run into problems, you can specify each executables path.
4. After that, you should be clear to go! You can use the same keybinds as you use in SciTE, so either press `F7` or `Ctrl-F7` > `Compile Script` to compile your program!
