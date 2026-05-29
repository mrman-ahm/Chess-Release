# Chess Release

A Windows chess game release package with included audio, sprites, DLLs, save data, and the Stockfish engine.

## Download and Play

The easiest way to play is to download the complete ZIP:

[Download Chess Release for Windows](https://github.com/mrman-ahm/Chess-Release/releases/latest/download/Chess-Release-Windows.zip)

After downloading:

1. Extract the ZIP file.
2. Open the `RELEASE` folder.
3. Double-click `chess.exe`.

## Download with Git

This repo uses Git LFS for the large Stockfish engine file. If you clone the repo, run these commands:

```powershell
git lfs install
git clone https://github.com/mrman-ahm/Chess-Release.git
cd Chess-Release
git lfs pull
cd RELEASE
.\chess.exe
```

## Notes

- Keep everything inside the `RELEASE` folder together.
- The game needs the included DLLs, audio, sprites, data, and Stockfish files.
- If `chess.exe` does not open after cloning, run `git lfs pull` from inside the `Chess-Release` folder.
