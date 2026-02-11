# ClipboardTyper

ClipboardTyper is a lightweight macOS menu bar app that helps with environments like Citrix/RDP where paste is blocked.

When you press the global shortcut, it waits 10 seconds and then types the current clipboard text into the focused application.

## Current behavior

- Runs as a menu bar app (`CT`).
- Global shortcut is configurable from `CT -> Settings…` (default `Command + Shift + V`).
- Delay before typing is configurable (default `10` seconds).
- Delay between keystrokes is configurable (default `0` ms).
- Feedback menu supports both email and GitHub issue reporting.
- Replaces any previous pending trigger if you press the shortcut again.
