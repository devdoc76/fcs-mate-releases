# FCS Mate

**Free flow cytometry analysis software.** Open FCS files apply gating strategies, and analyze your data, on macOS, Windows and Linux.

## Download

Always the latest version:

| System | Download |
|---|---|
| macOS (Apple Silicon) | [FCS-Mate-macOS.zip](https://github.com/devdoc76/fcs-mate-releases/releases/latest/download/FCS-Mate-macOS.zip) |
| Windows | [FCS-Mate-Windows.exe](https://github.com/devdoc76/fcs-mate-releases/releases/latest/download/FCS-Mate-Windows.exe) |
| Linux | [FCS-Mate-Linux.tar.gz](https://github.com/devdoc76/fcs-mate-releases/releases/latest/download/FCS-Mate-Linux.tar.gz) |

Older versions and release notes are under [Releases](https://github.com/devdoc76/fcs-mate-releases/releases).

## What it does

- Opens FCS files with channel names and marker labels, several files side by side in tabs
- Dot plots, density plots and filled contour plots, with linear, log and biexponential (logicle) axes
- Polygon, rectangle and quadrant gates, with gate hierarchy and a statistics table (events, % of total, % of parent, % of grandparent)
- Saves gates, layout and views as protocols and copies them from one file to another
- Export of plots as image or vector graphics
- Light and dark theme

## Installation

The apps are not code-signed, so your system shows a warning the first time. That is expected.

**macOS**
1. Unzip `FCS-Mate-macOS.zip` and drag *FCS Mate* into your Applications folder.
2. On the first start, right-click the app and choose **Open**, then confirm.
   If macOS still refuses, run this once in the Terminal: `xattr -dr com.apple.quarantine "/Applications/FCS Mate.app"`

**Windows**
1. Run `FCS-Mate-Windows.exe`. No installation is needed.
2. If Windows SmartScreen appears, click **More info**, then **Run anyway**.

**Linux**
1. Unpack with `tar xzf FCS-Mate-Linux.tar.gz`.
2. Start with `./FCS-Mate`.

## Intended use and disclaimer

For private use only. Not a medical device. Not for clinical or diagnostic use. The author accepts no liability for analyses, results or conclusions drawn from this software, including diagnostic conclusions.

## About

Designed and directed by Dr. Georg Slavka.

This repository only hosts the finished builds. The source code is not public.
