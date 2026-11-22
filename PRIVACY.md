# Privacy Policy

Vayu is a local app. What you type, search, open and ask stays on your computer. The only thing
the author receives is a small set of anonymous usage counts, listed below, so they can see how many
people use Vayu and which parts are worth improving.

## What stays on your computer

- Your settings, your custom commands, your notes, and your usage history: stored in a local
  database at `%LOCALAPPDATA%\CommandPalette`, never sent anywhere.
- Your typed text: kept only in memory while the window is open (and briefly after, so you can
  come back to it), never written to a file in plain form except your own notes.
- A local index of your app list and file names, built on your computer, for search. It never
  leaves your computer.

## What can leave your computer, and when

- **Anonymous usage counts:** always, as described in the next section. Never anything you typed.
- **Only if you set up your own AI key:** when you ask Vayu to understand a multi-step sentence,
  that sentence, a short list of apps/files it thinks might be relevant, and your request are sent
  directly from your computer to the AI provider you chose (for example Anthropic, OpenAI, Groq, or
  a model running on your own PC). This goes straight from you to them. It does not pass through
  any server the author runs, because there isn't one.
- **Your API key:** stored in Windows Credential Manager, protected by your Windows login. It is
  never written to a plain file, logged, or sent to the author.
- **Checking for updates:** Vayu may check a small file hosted on GitHub to see if a newer version
  exists. This request carries no personal information: not your name, not your usage, nothing
  identifying you beyond what any web request normally reveals (your IP address, to GitHub, the
  same as visiting any web page).

## Anonymous usage counts

Vayu sends a few anonymous counts to the author. This is always on. It is how the author knows how
many people use Vayu, whether they come back, and which features get used.

**What is sent:**

- A random install id, made the first time Vayu runs. It is not linked to you, your account, or your
  computer, and it is not made from any hardware id.
- The Vayu version, whether it came from GitHub or the Microsoft Store, the Windows build number, the
  display scale (for example 125%), and the language of your Windows (for example "en", without the
  region).
- When Vayu was installed, started, updated (old and new version), and once a day that it was used.
- Which setup pages were reached, and at the end of setup only the kind of AI picked (none, a Claude
  or ChatGPT plan, your own key, or a model on your PC) and whether the shortcut is the Windows key
  or your own.
- Once a day, how many times things were used: how often the window was opened, and how many apps,
  files, folders, settings, commands, notes, web searches, sums and AI questions were opened or
  asked. Only the number, never which one.
- For AI questions, only the kind of AI used and, if one failed, the rough reason (no internet,
  sign-in problem, refused, too slow, or other).
- If Vayu crashes: the place in Vayu's code where it happened and a short error message with any
  file paths and quoted text removed. It is sent the next time Vayu starts.

**What is never sent:** anything you type or search, file or folder names or paths, the names of your
apps, your AI questions or answers, your notes, your user name, your computer's name, or any
hardware id.

**Where it goes:** to PostHog, an analytics service, on its servers in the European Union. Vayu asks
it not to look up a location from your connection. The counts are sent over HTTPS. If you are
offline they wait in a small file in your user folder and go out later.

## What the author never receives

Your typed text, your searches, your files, your notes, your AI conversations, your AI key, or
anything that says who you are. There is no account and nothing to sign in to.

## Children

Vayu is not directed at children and does not knowingly collect information from anyone.

## Changes

This policy may be updated for a future release. Material changes will be noted in that release.

## Contact

Questions about this policy: open an issue on this repository.
