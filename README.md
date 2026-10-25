<div align="center">

<img src="assets/logo.png" width="112" alt="Cursora logo">

# Cursora

### Your AI companion, right at your cursor.

Select anything &nbsp;·&nbsp; press <kbd>Ctrl</kbd> + <kbd>G</kbd> &nbsp;·&nbsp; ask

<a href="https://github.com/priyansh1210/cursora-releases/releases/latest"><b>Download the latest version</b></a>
&nbsp;&nbsp;|&nbsp;&nbsp; Windows 10 / 11 &nbsp;·&nbsp; Linux

</div>

---

You're reading an error message, a paragraph in a PDF, or a contract in your browser, and you have a question about it. With Cursora you don't copy, paste or switch windows. **Select it, press the hotkey, and a small chat bubble opens right where your mouse is**, with your selection already attached. Ask, read the answer, press the hotkey again, and you're back where you were.

Use an AI model on your own computer, or your own key for a cloud service. Nothing goes anywhere you didn't choose.

<div align="center">
<img src="assets/bubble.png" width="420" alt="The Cursora bubble answering a question">
&nbsp;&nbsp;
<img src="assets/skills.png" width="420" alt="Typing / in the bubble lists the skills">
</div>

## Download

| | |
|---|---|
| **Windows 10 / 11** (64-bit) | `Cursora_<version>_x64_en-US.msi` |
| **Linux**, Debian and Ubuntu | `Cursora_<version>_amd64.deb` |
| **Linux**, Fedora | `Cursora-<version>-1.x86_64.rpm` |
| **Linux**, any distribution | `Cursora_<version>_amd64.AppImage` |

Get them from the **[latest release](https://github.com/priyansh1210/cursora-releases/releases/latest)**. Each one includes Cursora's built-in AI engine, so there's nothing else to install.

> [!NOTE]
> **Windows may say "Windows protected your PC"** when you open the installer. Cursora is new and not yet signed with a paid certificate, so Windows doesn't know it yet. Click **More info**, then **Run anyway**. A **Microsoft Store** version, signed by Microsoft and free of this warning, is on its way.

## What it does

**Works with anything you can select.** Browsers, PDF viewers, Word and Excel, editors, terminals, chat apps, and even files and folders in File Explorer. Nothing selected? The bubble opens as a plain chat.

**A bubble, not another window.** It opens at your cursor and streams the answer as it's written, with formatted text and highlighted code. Ask follow-up questions, or press **Expand** to continue in a bigger window.

**Snip anything on screen.** Press <kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>G</kbd> and drag a box around an image, a chart, a video frame or a scanned page, then ask about it. This works with AI models that can read images.

**Skills, one word away.** Type `/` in the bubble:

| | |
|---|---|
| `/summary` | Summarize the selection in a few bullet points |
| `/explain` | Explain what it means |
| `/simplify` | Rewrite it in simpler words |
| `/define` | Define a word or phrase |
| `/translate <language>` | Translate it |
| `/fix` | Fix grammar, spelling and punctuation |
| `/rewrite <tone>` | Rewrite it in another tone |
| `/code` | Explain what a piece of code does |
| `/bugs` | Find bugs in it |

You can make your own skills too, and save any question you asked as one.

**A companion with a personality, or none.** Pick a persona (Cursora, Ada, Arjun or Sage), make your own with its own name, tone and level of detail, or turn personality off for the plain model.

**History.** Conversations stay on your computer, searchable, for 90 days by default. You can switch saving off.

**Updates itself.** Cursora checks this page once a day. When there's a new version, it says so in its tray menu, and one click installs it.

<div align="center">
<img src="assets/setup.png" width="420" alt="First-time setup: choose an AI source">
</div>

## Your model, your choice

| On your computer | In the cloud, with your own API key |
|---|---|
| **Built-in engine:** choose a `.gguf` model file. Works fully offline. | **OpenAI**, **Anthropic**, **Google Gemini** |
| **LM Studio**, found automatically | **OpenRouter**, **Groq**, **DeepSeek**, **Mistral** |
| **Any OpenAI-compatible server:** llama.cpp, vLLM, Jan, LocalAI, KoboldCpp | **Any OpenAI-compatible service** |

A short setup on first start helps you choose, and checks that your model answers before you begin.

<div align="center">
<img src="assets/models.png" width="640" alt="Settings: models and providers">
</div>

## Private by design

- **No account, no telemetry, no analytics.** Cursora talks only to the AI models you set up, plus the once-a-day update check, which downloads one small file from this page and sends nothing about you. You can turn it off.
- **Local-only mode:** one switch, and nothing leaves your computer.
- **Personal details are hidden before they reach a cloud model.** Email addresses, phone numbers, card numbers, IBANs, API keys, and Aadhaar and PAN numbers are replaced with placeholders, then put back in the answer on your side. **What will be sent** shows the exact text before it goes.
- **Blocked apps:** Cursora never reads from password managers, and you can block any other app in one click.
- **API keys stay in your system's keychain** (Windows Credential Manager or the Linux Secret Service), never in a file or a log.
- **Your clipboard is left as it was**, and running programs in a terminal are never interrupted.

<div align="center">
<img src="assets/privacy.png" width="640" alt="Settings: local-only mode and blocked apps">
</div>

## Platforms

| | Windows 10 / 11 | Linux (X11) | Linux (Wayland) |
|---|:---:|:---:|:---:|
| Hotkey | Yes | Yes | Through a desktop shortcut |
| Selected text | Yes | Yes | Yes, with `wl-clipboard` |
| Selected files | Yes | Yes | No |
| Bubble at the cursor | Yes | Yes | Centered on screen |
| Snip | Yes | Yes | From a copied screenshot |

## Getting started

1. Download and install Cursora for your system from the [latest release](https://github.com/priyansh1210/cursora-releases/releases/latest).
2. Follow the short setup: choose an AI model, a personality and your hotkeys.
3. Select some text anywhere and press <kbd>Ctrl</kbd> + <kbd>G</kbd>.

<details>
<summary><b>Tips</b></summary>

- <kbd>Ctrl</kbd> + <kbd>G</kbd> is "Go to line" in some editors. You can choose another hotkey in **Settings → General**.
- To read apps that run as administrator, turn on **Settings → General → Run as administrator** (Windows, installed from the `.msi`).
- On Linux with GNOME, the tray icon needs the AppIndicator extension (Ubuntu has it). Everything also works without it.
- On Wayland, bind `cursora --ask` to a keyboard shortcut in your desktop's settings. Settings → General shows the exact command.

</details>

## About this page

This repository hosts Cursora's installers and the small file its updater reads. Each installer comes with a `.sig` signature, so Cursora installs an update only if it was signed by its developer. Cursora's source code is not public.

Cursora is in **early preview (version 0.1)**. Found a problem or have an idea? [Open an issue](https://github.com/priyansh1210/cursora-releases/issues).

<div align="center">
<sub>Made with Tauri, Rust and React.</sub>
</div>
