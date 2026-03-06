# smux

A native terminal multiplexer for macOS built for AI agents.

Run agents in parallel across split terminals and get notified when they finish.


## Features

- **Split terminals, run agents in parallel** — Split horizontally or vertically and manage everything at once.
- **Get notified when agents need you** — Turn on watch mode for any terminal. When an agent finishes its task, you get notified (with ring, sound or native push).
- **Workspaces** — Group related terminals into workspaces and switch between them.
- **Keyboard-driven** — Split, navigate, zoom, close, switch — everything is one shortcut away.
- **Session persistence** — Layout, terminals, and everything are saved and restored automatically.
- **Native and fast** — Written in Swift for macOS.

## Install

Requires macOS 14 or later. Free and open source.

[Download the latest release](https://github.com/gergomiklos/smux/releases)

<img width="1374" height="1019" alt="Screenshot 2026-03-06 at 12 15 49" src="https://github.com/user-attachments/assets/ab2322c8-1d00-4e45-95f9-bf7b64a34109" />

## Keyboard Shortcuts

| Action | Shortcut |
|---|---|
| Split right | `Cmd + Right` |
| Split down | `Cmd + Down` |
| Close terminal | `Cmd + W` |
| Zoom terminal | `Cmd + Shift + Enter` |
| Toggle notifications | `Cmd + B` |
| Navigate panes | `Option + Arrow keys` |
| Switch workspace | `Cmd + 1-9` |
| Next / previous workspace | `Option + Shift + Arrow keys` |
| New workspace | `Cmd + Shift + T` |
| Show all shortcuts | `Cmd + /` |

## Build from source

Open `smux.xcodeproj` in Xcode 15+ and hit `Cmd + R`.

## License

MIT
