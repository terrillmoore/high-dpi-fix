# high-dpi-fix

How to improve apps that don't work with high-DPI displays on Windows 10.

## Background

I find that many engineering applications don't properly handle high-resolution displays on Windows 10 (sometimes called High-DPI or Retina displays).  The result is ugly text boxes, tiny icons, etc.

Luckily, there's a simple fix.

## Procedure

1. Using File Explorer, find the `.exe` file that has problems in Windows File Explorer. If you search for the file using Windows+"name", you want to keep opening the file location until you get to the `.exe` (or `Application`). You'll see this in the clip below.

2. Right-click>`Properties`

3. Select `Compatibility`.

4. At bottom of tab, select `Change high DPI settings`.

5. On the resulting window, at the bottom, select `[x] Override high DPI scaling behavior. Scaling performed by:`.

6. Change the dropdown to `System (Enhanced)`.

## Animated run-through

This GIF will give you a feeling for the process.

![Animated run-through of procedure](assets/high-dpi-fix.gif)
