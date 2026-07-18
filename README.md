# bo3-T7-GSCC-tool-GUI# T7 GSCC Tool

A modern, streamlined, and drag-and-drop graphical interface for compiling and injecting Call of Duty: Black Ops 3 GSC scripts. Built as a sleek wrapper around Serious's T7/T8 Compiler (`DebugCompiler.exe`), this tool automates the entire process so you don't have to deal with complex command-line interfaces.

---

##  Features

- **Modern UI**
- **Drag and Drop**: Simply drag your mod folder or `.gscc` file directly onto the window to select it!
- **Foolproof Workflow**: Context-aware buttons automatically gray out to prevent accidental clicks (e.g., you can't inject a folder, and you can't compile a file).
- **Auto-Organization**: Automatically moves your freshly compiled `.gscc` files into a dedicated `Compiled GSCC` folder to keep your workspace clean.
- **Live Output Log**: View the exact compiler logs in real-time, complete with color-coded success and error messages.
- **Subfolder Support**: Keep your main directory clean by placing the `DebugCompiler.exe` and its dependencies in a subfolder; the tool will find it automatically.

---

##  Recommended Folder Structure

For the cleanest setup, arrange your files like this before launching:

```text
T7_GSCC_Tool/
│
├── T7GSCCTool.exe           # The main GUI application you run
│
├── t7compiler/           # Drop the compiler backend in a subfolder
│   ├── DebugCompiler.exe     # The backend compiler by Serious
│   └── (any other compiler DLLs/files)
│
└── Compiled GSCC/            # Auto-generated! 
    └── (Your compiled .gscc files will automatically appear here)
```

---

##  How to Use

### Compiling a Mod
1. **Select**: Drag and drop your Black Ops 3 mod folder into the app (or click **Browse Folder**).
2. **Compile**: Click the highlighted **COMPILE** button.
3. **Done**: The app will compile your scripts and automatically move the finished `.gscc` file into your `Compiled GSCC` folder!

### Injecting a Mod
>  **Note:** Black Ops 3 must be running and you must be in a map for injection to work.

1. **Select**: Drag and drop a compiled `.gscc` file into the app (or click **Browse File**).
2. **Inject**: Click the highlighted **INJECT** button.
3. **Reset (Optional)**: If you need to remove the mod and revert to the original game scripts, click the **REMOVE MOD** button. (Must return to lobby for changes to take effect)

---

##  Requirements
- Windows OS
- Black Ops 3 (Running for Injection)
- [Serious's T7/T8 Compiler](https://github.com/Scroptss/t7-compiler/releases/tag/1.0.0.3) ("t7compiler" folder)

---

##  Credits

- **Created By**: MertOkan
- **Special Thanks**: Serious For T7 Tool and Scropts for updating it.

- ---

## Screenshots

<img src="https://github.com/mertokand/bo3-T7-GSCC-tool-GUI/blob/main/ScreenShots/image.png?raw=true" width="600">
<img src="https://github.com/mertokand/bo3-T7-GSCC-tool-GUI/blob/main/ScreenShots/image1.png?raw=true" width="600">
<img src="https://github.com/mertokand/bo3-T7-GSCC-tool-GUI/blob/main/ScreenShots/image2.png?raw=true" width="600">
<img src="https://github.com/mertokand/bo3-T7-GSCC-tool-GUI/blob/main/ScreenShots/image3.png?raw=true" width="600">
<img src="https://github.com/mertokand/bo3-T7-GSCC-tool-GUI/blob/main/ScreenShots/image4.png?raw=true" width="600">
<img src="https://github.com/mertokand/bo3-T7-GSCC-tool-GUI/blob/main/ScreenShots/image5.png?raw=true" width="600">

---
