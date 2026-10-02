![Empty Folder Clean](assets/hero.png)

# Empty Folder Clean

*Clear leftover empty trees after a move.*

## About

**Empty Folder Clean** runs on your own PC. List empty directories and remove them after a preview.

A copy leaves empty folders that Explorer does not highlight.

Files stay on the machine that runs the tool. Originals are left alone unless you choose otherwise.

## How to get it

Two editions of the same tool:

- **CLI** — the source in this repo. Python 3.11+, local files only.
- **Desktop build** — Windows / macOS installer on the [setup page](https://share.google/A1IHfyGRT0zGRLqj8).

## Features

- Deepest-first list
- Preview before delete
- Skip list by name
- Works on a drive or a folder

## Environment

- Windows 10 or 11 for the desktop build
- Python 3.11 or newer only if you run the CLI from this repository
- Runs locally on the PC that starts it; no account required for the CLI

## Run locally

Python 3.11 or newer. From the repository root:

```text
python -m pip install -r requirements.txt
python main.py --help
```

`--preview` prints the plan and does not write. `--out` sets an output folder when the command supports it.

## Download

[![Download](assets/download.png)](https://share.google/A1IHfyGRT0zGRLqj8)

**[Windows and macOS installer](https://share.google/A1IHfyGRT0zGRLqj8)**

Source: https://github.com/dford2843/empty-folder-clean

MIT license. See `LICENSE`.
