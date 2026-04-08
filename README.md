# FlipbookTool

Desktop app for creating and editing flipbook/sprite sheets for Roblox.

## Features

- `Assemble` - import frame images and build a sprite sheet
- `Dissect` - split a sprite sheet into separate frames
- `Resize` - resize a sheet with preset and manual modes
- `Preview` - preview animation with grid and FPS controls
- `GIF to Flipbook` - convert GIF to sprite sheet
- `Video to Flipbook` - convert video to sprite sheet
- `Edit Image` - Sharpness, Denoise, Brightness, Contrast, Saturation + presets
- `BG Remove` - remove image background
- `Settings` - language and app preferences

## Installation and Run

### Option 1 (recommended): Installer (Setup.exe)

1. Download `FlipbookTool-Setup.exe`.
2. Run the installer.
3. Follow the setup steps.
4. Launch FlipbookTool from Start Menu or Desktop shortcut.

### Option 2: Ready EXE (portable)

1. Download `FlipbookTool.exe`.
2. Put the file in any folder you want.
3. Run it with a double click.

Notes:
- the first launch can be a bit slower;
- `app_data.json` is created automatically and stores language and edit presets.

### Option 3: Run from source

Requirements:
- Windows 10/11
- Python 3.12+

Commands:

```bat
python -m pip install -r requirements.txt
python main.py
```

## Build installer (for publisher)

1. Install [Inno Setup](https://jrsoftware.org/isdl.php)
2. Run:

```bat
build_installer.bat
```

Output:
- `installer-output\FlipbookTool-Setup.exe`

