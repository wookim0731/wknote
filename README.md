# wknote

Notebooks for Mac and iPhone that sync through your own iCloud, with an MCP server so any AI app on your Mac that supports MCP can save notes into them.

## Support

Questions, bugs and requests: [open an issue](https://github.com/wookim0731/wknote/issues) or email wookim0731@gmail.com.

**Shortcuts.** Every Mac shortcut is listed in Settings (⌘,).

**Images.** Paste or drop an image with ⌘V. Press Delete once to select an image and again to remove it.

**Sync.** Sign in to the same iCloud account on your Mac and iPhone. Pages and images sync on their own.

**AI apps (MCP).** The Mac app ships a standard MCP server, so any MCP client, such as Claude, Cursor or VS Code, can list, search, read and write your pages. Point your client at:

```
/Applications/wknote.app/Contents/MacOS/wknote-mcp
```

In Claude Code, for example:

```
claude mcp add wknote /Applications/wknote.app/Contents/MacOS/wknote-mcp
```

Then ask your AI to "save this to wknote".

## Privacy Policy

wknote does not collect any personal data. Your notes and images are stored on your devices and, when iCloud is on, in your private iCloud database through Apple's CloudKit. The developer has no access to that data. wknote has no accounts, analytics, ads or tracking, and does not share data with anyone. The Mac app's MCP server runs only on your Mac and reads or writes your notes only when an AI app you set up asks it to.

Contact: wookim0731@gmail.com

Last updated: November 8, 2026
