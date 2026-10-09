# Installing Volpi

Download the zip for your computer from the [README](README.md#download), unzip it and
open the `Volpi <version>` folder. It holds the installer, `README.txt` (these steps),
`CHANGELOG.txt`, `LICENSE.txt` and `THIRD_PARTY_NOTICES.txt`.

The beta installers are not signed yet, so your computer may warn you the first time.
The steps below get past that warning.

## Windows 10 or 11

1. Double-click `Volpi_<version>_x64-setup.exe`.
2. If "Windows protected your PC" appears, choose **More info**, then **Run anyway**.
3. Follow the installer. Volpi needs Microsoft Edge WebView2, which is part of Windows 11
   and most Windows 10 computers; if it is missing, the installer downloads it.

To remove Volpi: Settings, Apps, Volpi, Uninstall.

## macOS

Use the Apple Silicon zip for M1 and later Macs, and the Intel zip for older ones.

1. Open the `.dmg` file and drag Volpi into Applications.
2. The first time, right-click Volpi in Applications and choose **Open**, then **Open**
   again. If macOS still refuses, open System Settings, Privacy & Security, and choose
   **Open Anyway** next to the message about Volpi.

To remove Volpi: drag it from Applications to the Bin.

## Linux

The zip holds a `.deb` and an `.rpm` package. In a terminal, in the unzipped folder:

| Distribution | Install | Remove |
|---|---|---|
| Debian, Ubuntu, Linux Mint and similar | `sudo apt install ./Volpi_<version>_amd64.deb` | `sudo apt remove volpi` |
| Fedora, openSUSE and similar | `sudo dnf install ./Volpi-<version>-1.x86_64.rpm` | `sudo dnf remove volpi` |

Volpi then appears in your applications menu.

## Your files

A branch (a Volpi project) is a folder you choose. Your PDFs, notes, papers and data stay
there as ordinary files; Volpi keeps its own records (history, highlights, references) in
the branch's `.volpi` and `annotations` folders. Back up the branch folder as you would any
other folder. Removing Volpi does not remove your branches.

## Updating

From Volpi 0.1.1, Home checks for new versions in the background. The button at the
bottom right says **Updated** when this version is current. When it says **Update
available**, choose it, then **Update and restart**. Updates are checked before they are
installed, and your branches stay on your computer.

You can also download the newest zip and install it over the old version; your branches
and settings stay as they are. Volpi 0.1.0 has no updater, so it needs this one manual
upgrade.
