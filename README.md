<p align="center">
  <img src="assets/logo/logo.png" width="96" alt="Vayu logo">
</p>

<h1 align="center">Vayu</h1>
<p align="center"><b>A free, fastest command palette launcher application that works completely offline for Windows.</b></p>

<p align="center">
  <a href="#download">Download</a> ·
  <a href="#features">Features</a> ·
  <a href="#how-it-compares">Comparison</a> ·
  <a href="#privacy--security">Privacy</a> ·
  <a href="#feedback--issues">Feedback</a>
</p>

---

## Download

**[Download Vayu for Windows](https://github.com/YashPatkar/vayu/releases/latest/download/vayu.exe)**: one `.exe`, no installer, about 4 MB.

Requires Windows 10 or 11 (64-bit). No .NET, no runtime, no admin rights. Run it once and it starts
with Windows from then on. Press **Ctrl+Alt+Space** to open it (you can change this in Settings).

Vayu updates itself: when a new version is out, an update row appears in Settings.

## Why Vayu

Most launchers on Windows are either heavy (hundreds of megabytes, many background processes) or do
only one thing. Vayu is built from scratch in Rust on the plain Windows API, with no Electron, no
WebView and no .NET, so it opens in about 2 milliseconds and uses almost nothing while it waits.

Press your shortcut. Type a name, or a whole sentence. Get it done.

## Features

- **Works offline.** Search, the terminal, notes, sites and settings all run on your PC with no
  internet. Only the optional AI and the update check ever go online.
- **Find anything fast.** Apps, Windows settings (`!`), and files and folders (`/`), all in one box.
  The results you pick most often come first.
- **Open anything by name.** "open notion" opens the app if you have it, otherwise the website,
  otherwise it offers a web search. No dead ends.
- **Sites in any browser.** "open chatgpt on brave" or "open youtube using my work edge" opens the
  site in that browser, in the right profile. Add your own sites with just a link.
- **Say it in a sentence.** "open docker, then open my project in vs code": Vayu does every step, in
  order.
- **Your own AI, your own key** (optional). Bring any provider you like, or run a model on your own
  PC. Vayu never bundles or resells AI access.
- **An instant terminal**, built in. Start with `>` to run a command right in the box.
- **Quick notes** with `@`, without opening another app.
- **Calculator and web search** as fallbacks, so you're never stuck with "nothing found".
- **Your shortcut, your way.** Press the keys you want and save. Starts with Windows by default.

## How it compares

| | **Vayu** | PowerToys Run | PowerToys Command Palette |
|---|---|---|---|
| Shortcut → window shown | **~2 ms** | ~35 ms | ~3 ms |
| Download size | **~4 MB** | part of an 800+ MB suite | part of an 800+ MB suite |
| Memory while idle | **~11 MB** | ~190 MB | not measured |
| Runtime required | **None** | .NET | .NET |
| Works fully offline | **Yes** | Yes | Yes |
| Multi-step sentences | **Yes** | No | No |
| Your own AI key, no middleman | **Yes** | No | No |

*Measured on the same machine in the same session; your results may vary.*

## Privacy & security

**Your data stays on your PC, and the author never sees it.** Vayu has no server, no account, no
telemetry and no analytics. Your apps, your files and what you type stay on your own device.

- **No telemetry, ever.** Vayu has no way to phone home.
- **No bundled AI, no middleman.** If you set up AI, your sentence goes straight from your PC to the
  provider *you* chose. Your key is kept in Windows Credential Manager, never in a plain file.
- **No admin rights needed.** Nothing is installed outside your own user folder.
- **Every update is signed.** Vayu checks a cryptographic signature before installing any update.
- **Asks before risky steps.** Closing an app, running a command the AI chose, or running a tool for
  the first time always asks you first.

Full details: [Privacy Policy](PRIVACY.md).

## Free to use

Vayu is free to download and use. This repo holds the app and its releases, not the source code. See
the [Terms of Use](TERMS.md) for what you may do with it (use it anywhere: yes; resell or rebrand
it: no).

## Feedback & issues

Found a bug or have an idea? [Open an issue](https://github.com/YashPatkar/vayu/issues).

If something breaks and you'd rather not post it publicly, email **yash.patkar2004@gmail.com** with
the subject **`Vayu bug report`** (exactly that, so it doesn't get lost). Say what happened, what you
were doing, and your Vayu version (shown in Settings).
