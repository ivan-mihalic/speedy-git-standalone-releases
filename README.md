# Speedy Git Standalone

**A fast Git history viewer for macOS.** It shows your repository's commit graph,
branches, tags and diffs in a native app — and lets you do the everyday work
from there: check out, merge, rebase, cherry-pick, stash, compare, manage
worktrees.

It is for people who spend their day reading and reshaping Git history and would
rather have a real window for it than a panel inside an editor.

## Download

Go to
**[Releases](https://github.com/ivan-mihalic/speedy-git-standalone-releases/releases/latest)**
and download the `.dmg`:

```
SpeedyGitStandalone-<version>-arm64.dmg
```

Open it, drag **Speedy Git Standalone** to your **Applications** folder, and
launch it.

The app is **signed with an Apple Developer ID and notarised by Apple**, so it
opens normally the first time — no "unidentified developer" warning, no
right-click → Open, no Terminal commands to clear a quarantine flag.

## Requirements

|  |  |
|---|---|
| **macOS** | 12 (Monterey) or later |
| **Mac** | Apple Silicon — M1 and later |
| **Git** | Speedy Git Standalone drives your real `git`. Most Macs already have it; if not, `xcode-select --install` installs Apple's command-line tools. |

## Updates

Speedy Git Standalone updates itself from this repository. Open
**Speedy Git Standalone → About** and press **Check for updates**: it tells you
which version you would move to, and each step after that is yours to take —
**Download update**, then **Restart & Install**. Nothing is installed behind
your back.

## Built on Speedy Git by onlineeric

This app exists because of
**[speedy-git-ext](https://github.com/onlineeric/speedy-git-ext)** by
**[onlineeric](https://github.com/onlineeric)** — an excellent, performance-first
Git graph extension for VS Code, released under the **MIT licence**. Its
interface is the interface you see here: this project takes that open-source UI
and gives it its own window outside the editor.

If you use VS Code or Cursor, install the original from the marketplace — it is
free, it is open source, and it is the better fit there. Please star the
[upstream project](https://github.com/onlineeric/speedy-git-ext); it earned it.

The full licence text for the upstream project — and for Electron, Monaco,
React and every other component this app is built from — ships inside the app:
**About → Licences**. (It is also in the app bundle itself, under
`Contents/Resources/licenses/`.)

## About this repository

This repository holds **releases only**. There is no source code here: the app's
own source is not published. What you will find is the signed download, the file
the in-app updater reads, and this page.

Speedy Git Standalone is **free to download**.

## Licence

Speedy Git Standalone is © Ivan Mihalic and is distributed as a binary; its
own source is not open. It incorporates
[speedy-git-ext](https://github.com/onlineeric/speedy-git-ext) © Eric Cheng
(onlineeric) under the MIT licence, along with other open-source components,
each under its own permissive licence. Every one of those licences travels with
the app and is readable in **About → Licences**.
