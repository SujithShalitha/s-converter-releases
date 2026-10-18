# Troubleshooting and FAQ

## The Quick Convert shortcut does nothing

- S Converter must be running: look for its icon in the system tray (near the clock). Open it once from the Start menu.
- Another app may already use the keys. **Settings → Quick Convert shortcut** tells you, and lets you pick another, such as <kbd>F8</kbd>.
- Select the files first, in File Explorer, on the desktop or in an Open/Save dialog. With nothing selected, the shortcut uses the image on the clipboard, if there is one.

## The window opened white

On some PCs the graphics driver doesn't start in time. S Converter notices, switches to software drawing and restarts itself; it remembers this, so it only happens once.

## "Windows protected your PC"

That's SmartScreen for apps without a paid signing certificate. Click **More info → Run anyway** once, or install from the [Microsoft Store](https://apps.microsoft.com/detail/9NKD1BD2RM1X), which never shows it. See [Install and update](install.md).

## A file won't convert

- Check [Supported formats](formats.md).
- A file that's still downloading, or open in another program, can fail. Close it and try again.
- Password-protected PDFs and archives: S Converter asks for the password.
- The **Conversion complete** screen lists each failed file and why.

## A file is still over my size limit

With **Max size**, S Converter saves the smallest version it can make and tells you when a limit can't be reached. Try a larger limit, or a smaller resolution. See [Make it fit](make-it-fit.md).

## Where are my files?

Next to the originals with **SC** in the name, unless you chose a folder. The **Conversion complete** screen and [History](watch-history.md) have buttons to show them.

## Is it really free?

Yes. No ads, no trial, no account, no limits, and no watermark added to your files. If it helps you, you can [buy the developer a coffee](https://www.buymeacoffee.com/SujithShalitha).

## Something else

Open an issue on [S Converter's GitHub page](https://github.com/SujithShalitha/s-converter-releases/issues) with what you did and what happened.

[← All topics](README.md)
