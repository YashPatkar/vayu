<h1 align="center"><img src="assets/logo/logo.png" width="44" align="absmiddle" alt=""> Vayu</h1>
<p align="center"><b>A free, fastest command palette launcher application that works completely offline for Windows.</b></p>

<p align="center">
  <a href="https://github.com/YashPatkar/vayu/releases/latest/download/vayu.exe"><b>Download for Windows</b></a> ·
  <a href="#why-people-switch">Why switch</a> ·
  <a href="#everything-it-does">Features</a> ·
  <a href="#side-by-side">Comparison</a> ·
  <a href="#privacy">Privacy</a>
</p>

---

Press a shortcut. Type a name or a whole sentence. It's done before you finish blinking.

Vayu is a launcher like the ones you may already use, rebuilt from scratch to be **tiny, instant and
private**. One 4 MB file. No account. No subscription. No internet needed. It sits at **0% CPU**
while you're not using it, and opens in about **2 milliseconds**.

## Download

**[⬇ Download vayu.exe](https://github.com/YashPatkar/vayu/releases/latest/download/vayu.exe)** (about 4 MB)

1. Run it. There's no installer and no admin prompt.
2. Press **Ctrl+Alt+Space**. That's it.

Works on Windows 10 and 11 (64-bit). Nothing else to install. It starts with Windows from then on and
updates itself.

## Why people switch

- **It's instant.** About 2 ms from your key press to the window: faster than your screen can draw a
  frame. Other launchers can take 15 times longer.
- **It's light.** A 4 MB download, about 60 MB of memory after a full day of use, and 0% CPU when idle.
  Others take hundreds of megabytes of disk and memory, and keep working in the background.
- **It's free, really.** No paid plan, no "Pro" features, no trial that runs out. AI included, with your
  own key or a model on your own PC.
- **It's private.** Works completely offline. No account, no sign-in, no tracking. Nothing you type
  ever leaves your PC unless you choose to use an online AI.
- **It understands you.** Type "open notion" and it opens the app, or the website if you don't have
  the app. Type a whole sentence and it does every step.

## Everything it does

### Find and open

- **Apps, settings, files and folders** in one box. Type a few letters; the right thing comes first.
- **It learns.** What you pick most comes first next time, for the exact words you typed.
- **Windows settings** with `!` ("!bluetooth", "!display"), **files and folders** with `/`.
- **Open anything by name.** An app if you have it, a website if you don't, a web search if it's
  neither. Never a dead end.
- **Websites in the browser you want.** "open youtube on brave", "open chatgpt using my work edge":
  even the right browser profile.
- **Your own sites.** Paste a link once; open it by a word from its address forever.
- **Recently used** at the top: reopen what you used last with one key press. Pick how many, or
  turn it off.
- **Run as administrator, open file location, or hide** a result, right from the list.

### Do more in one go

- **Sentences with several steps.** "open docker, then open my project in vs code". Vayu does each
  step in order. No AI needed for everyday sentences.
- **Hindi and Hinglish** typed in Devanagari work too.
- **A terminal in the box.** Start with `>` to run a command and see the output right there. Risky
  commands ask before running.
- **Calculator.** Type `24*8/16`, press Enter to copy the answer.
- **Quick notes** with `@`: jot something down without opening another app.

### AI, your way (optional)

- **Bring your own AI**: a key from any cloud provider (Anthropic, OpenAI, Groq, Gemini and more), or
  a **model running on your own PC** (Ollama, llama.cpp) with no internet at all.
- Your key goes straight from your PC to the provider you picked. No middleman, no markup, no
  subscription.
- AI only steps in for sentences the built-in rules can't read. Everything else stays offline.

### For power users: Developer mode

- **Your own commands**: give any command a short name and run it from the box.
- **Your own tools**: point Vayu at a folder, and your AI coding assistant can write new tools for it.
  Each tool asks once before it ever runs.
- **Pick your terminal**: Command Prompt, PowerShell, Git Bash, WSL, whatever you have.

### Made to stay out of your way

- **Your shortcut, your way.** Press the keys you want and save. No typing key names.
- **Starts with Windows**, ready when you log in. Turn it off any time. Want it even sooner? Start
  it as a Windows service, at top priority.
- **A clean settings window**: clear sections, switches, and a search box to find any setting.
- **Remembers what you typed** if you click away, so nothing is lost.
- **Updates itself**, and checks every update's digital signature before installing it.
- **Dark, clean and smooth**: no flicker while you type.

## Side by side

Measured on the same laptop (Intel Core i5-12450H, 16 GB RAM, Windows 11), all three running at the same time, on 18 November 2026.

| | **Vayu** | Raycast | PowerToys Run |
|---|---|---|---|
| Space on disk | **4 MB** | 565 MB | 851 MB (PowerToys) |
| Memory after real use | **60 MB** | 348 MB | 111 MB |
| Highest memory seen | **76 MB** | 428 MB | 278 MB |
| CPU while idle | **0.00%** | 0.63% | 0.26% |
| Key press → window shown | **~2 ms** | not measured | ~35 ms |
| Runs without an account | **Yes** | Sign-in for Pro features | Yes |
| AI without a paid plan | **Yes** (your key or a local model) | No (Pro plan) | No AI |
| Multi-step sentences | **Yes**, no AI needed | With paid AI | No |

*Memory is the working set reported by Windows; for Raycast and PowerToys Run it includes their helper
process (highest memory is the main process alone). Idle CPU is measured over 30 seconds with each launcher hidden. Your numbers will differ by PC.*

## Privacy

**Your data stays on your PC, and the author never sees it.** Vayu has no server, no account, no
telemetry and no analytics.

- **No tracking, ever.** Vayu has no way to phone home.
- **Offline by default.** Only two things ever go online, and only if you use them: an online AI you
  set up yourself, and the update check (which sends nothing about you).
- **Your AI key** is kept in Windows Credential Manager, never in a plain file.
- **No admin rights.** Nothing is installed outside your own user folder.
- **Asks before risky steps**: closing an app, running a command the AI chose, or running a tool for
  the first time.

Full details: [Privacy Policy](PRIVACY.md).

## Free to use

Vayu is free to download and use, at home or at work. This repo holds the app and its releases, not
the source code. See the [Terms of Use](TERMS.md) (use it anywhere: yes; resell or rebrand it: no).

## Feedback & issues

Found a bug or have an idea? [Open an issue](https://github.com/YashPatkar/vayu/issues).

If something breaks and you'd rather not post it publicly, email **yash.patkar2004@gmail.com** with
the subject **`Vayu bug report`** (exactly that, so it doesn't get lost). Say what happened, what you
were doing, and your Vayu version (shown in Settings).
