<p align="center">
  <img src="icon_512.png" alt="LitLink app icon" width="180" />
</p>

<h1 align="center">LitLink — Virtual Audio Cable for Mac</h1>

<p align="center">
  A free virtual audio driver for macOS that routes system audio and microphone input to any application.<br/>
  One-toggle setup. No Audio MIDI Setup. No aggregate devices. Just works.
</p>

<p align="center">
  <a href="https://github.com/linguaholic/litlink-app/releases/latest/download/LitLink.pkg"><strong>Download LitLink Free</strong></a>&nbsp;&nbsp;·&nbsp;&nbsp;
  <a href="https://litpads.app/litlink">Website</a>&nbsp;&nbsp;·&nbsp;&nbsp;
  <a href="https://litpads.app/litlink/buy">Get LitLink Pro</a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/macOS-14%2B-blue?logo=apple&logoColor=white" alt="macOS 14+" />
  <img src="https://img.shields.io/badge/Apple-Signed%20%26%20Notarized-brightgreen?logo=apple&logoColor=white" alt="Signed and notarized" />
  <img src="https://img.shields.io/badge/Architecture-Universal%20(ARM%20%2B%20Intel)-orange" alt="Universal binary" />
  <img src="https://img.shields.io/github/v/release/linguaholic/litlink-app?label=Latest%20Release" alt="Latest release" />
  <img src="https://img.shields.io/github/downloads/linguaholic/litlink-app/total?label=Downloads" alt="Total downloads" />
</p>

---

## What Is LitLink?

LitLink is a virtual audio driver for macOS that creates a virtual audio device on your Mac. Any application — Discord, OBS, Zoom, QuickTime, or any DAW — can use this device as an audio input to receive system audio, microphone audio, or both.

Unlike BlackHole or other virtual audio cables that require manual Audio MIDI Setup configuration, LitLink includes a companion app that handles everything automatically with a single toggle.

---

## Features

### LitLink Free

Everything you need for basic audio routing — completely free, no account required, no time limit.

| Feature | Description |
|---------|-------------|
| **System Audio Passthrough** | Routes all system audio to the virtual device with one toggle. Automatically creates and configures the multi-output device. |
| **Mic Passthrough** | Combines your microphone audio with system audio into a single stream. No aggregate device setup needed. |
| **Companion App** | Menu bar app with visual controls, status display, and mic volume adjustment. |
| **Automatic Multi-Output Device** | LitLink creates the multi-output device and sets it as system default automatically. No Audio MIDI Setup required. |
| **Persistence** | Configuration survives restarts. Set it once, forget it. |
| **32-bit Float / 48 kHz Stereo** | Studio-grade audio quality at the kernel level. |
| **Built-in Help Guide** | Setup instructions for Discord, OBS, Zoom, and every supported application. |

### LitLink Pro — $3.99/mo or $29 Lifetime

Per-app audio routing for streamers, podcasters, and professionals who need precise control.

| Feature | Description |
|---------|-------------|
| **Per-App Audio Routing** | Select specific apps to route through LitLink using the macOS Process Tap API. |
| **Individual Volume Control** | Independent volume slider for each routed application. |
| **Per-App Mute** | Mute individual apps without stopping the audio tap. |
| **Real-Time Level Meters** | Visual audio level display per app. |
| **Parametric EQ** | Per-app and master parametric equalizer with visual frequency curve. |
| **Peak Limiter** | Per-app and per-bus brick-wall limiters with adjustable ceiling — prevents clipping in your stream or recording when multiple apps sum together. |
| **Routing Profiles** | Save and switch between different routing configurations. |
| **Global Hotkeys** | Keyboard shortcuts for per-app routing control. |
| **7-Day Free Trial** | Try all Pro features free for 7 days on both plans. |

---

## Quick Start

1. **Download** — grab [LitLink.pkg](https://github.com/linguaholic/litlink-app/releases/latest/download/LitLink.pkg) and run the installer
2. **Open LitLink** — the app runs in your menu bar
3. **Toggle System Audio Passthrough** — one click, done
4. **Select "LitLink Audio Bridge"** as the input device in Discord, OBS, Zoom, or any app
5. **Optional:** toggle Mic Passthrough to combine your voice with system audio

That's it. No Audio MIDI Setup. No multi-output device configuration. No master clock settings.

---

## Use Cases

| Use Case | How |
|----------|-----|
| **Share audio on Discord** | Toggle system audio passthrough, select LitLink Audio Bridge as input in Discord voice settings |
| **Capture system audio in OBS** | Add LitLink Audio Bridge as an audio input source in OBS |
| **Play audio in Zoom meetings** | Select LitLink Audio Bridge as your microphone in Zoom |
| **Record app audio in QuickTime** | Choose LitLink Audio Bridge as the microphone in a new audio recording |
| **Route soundboard to Discord/OBS** | Use [LitPads](https://litpads.app) for soundboard + LitLink for routing |
| **Stream with per-app control** | LitLink Pro: route Chrome audio without Spotify, or vice versa |
| **Podcast recording** | Capture specific application audio while excluding others |

---

## LitLink vs BlackHole vs Loopback

| | LitLink Free | LitLink Pro | BlackHole | Loopback |
|---|---|---|---|---|
| **Price** | Free | $3.99/mo or $29 | Free | $99 |
| **Setup** | One toggle | One toggle | Manual Audio MIDI Setup | Visual routing UI |
| **Mic Passthrough** | Built-in | Built-in | Not included | Manual wiring |
| **Per-App Routing** | — | Per-app with volume | — | Per-app with wires |
| **Multi-Output Device** | Automatic | Automatic | Manual | Automatic |
| **Companion App** | Included | Included | Not included | Included |
| **EQ** | — | Per-app + master | — | — |
| **Audio Quality** | 32-bit float / 48 kHz | 32-bit float / 48 kHz | 32-bit float / 48 kHz | 32-bit float / 48 kHz |

---

## Technical Specifications

| Spec | Value |
|------|-------|
| **Driver Type** | HAL (Hardware Abstraction Layer) audio plugin |
| **Audio Format** | 32-bit float, stereo |
| **Sample Rates** | 44.1 kHz, 48 kHz, 96 kHz |
| **Latency** | Near-zero (kernel level) |
| **Architecture** | Universal binary (Apple Silicon + Intel) |
| **Minimum macOS** | 14.0 Sonoma (Free), 14.2 (Pro per-app routing) |
| **Installer** | Signed with Developer ID, notarized by Apple |
| **Installer Size** | ~3.5 MB |

---

## Frequently Asked Questions

<details>
<summary><strong>Is LitLink really free?</strong></summary>
<br/>
Yes. LitLink Free includes mic passthrough, system audio passthrough, automatic multi-output device creation, the companion app, and the built-in help guide. No trial period, no time limit, no account required. These features are permanently free.
</details>

<details>
<summary><strong>How do I get LitLink Pro?</strong></summary>
<br/>
Download and install LitLink Free first. Open the app, scroll to the Pro section, and click "Buy LitLink Pro." Choose monthly ($3.99/mo) or lifetime ($29). Both plans include a 7-day free trial. After purchase, enter your transaction ID in the app and click Activate.
</details>

<details>
<summary><strong>Does LitLink work with Apple Silicon and Intel Macs?</strong></summary>
<br/>
Yes. LitLink is a universal binary that runs natively on Apple Silicon (M1, M2, M3, M4) and Intel Macs without Rosetta translation.
</details>

<details>
<summary><strong>Is LitLink safe to install?</strong></summary>
<br/>
LitLink is signed with a Developer ID certificate and notarized by Apple. macOS Gatekeeper verifies the signature before installation. The installer places the audio driver in the standard system audio plugin directory and the app in your Applications folder.
</details>

<details>
<summary><strong>Does LitLink add latency?</strong></summary>
<br/>
System audio passthrough operates at the kernel level with near-zero latency. Mic passthrough adds approximately 42ms through a minimal ring buffer, which is imperceptible in voice calls and streaming.
</details>

<details>
<summary><strong>How do I uninstall LitLink?</strong></summary>
<br/>
Open the LitLink app, go to the Status section, and click "Uninstall Driver." The app removes the driver, disables passthrough, restores your original audio output, and cleans up the multi-output device. Then delete LitLink from Applications.
</details>

<details>
<summary><strong>Which apps work with LitLink?</strong></summary>
<br/>
Any app that accepts audio input on macOS: Discord, OBS, Zoom, Google Meet, Twitch Studio, QuickTime, GarageBand, Logic Pro, Audacity, and any DAW or recording tool.
</details>

<details>
<summary><strong>Why don't some apps appear in per-app routing?</strong></summary>
<br/>
Apps only appear when actively producing audio. Start playback in the app and click Refresh App List.
</details>

<details>
<summary><strong>Can I use LitLink with LitPads?</strong></summary>
<br/>
Yes. LitPads is a custom soundboard app for Mac, iPad, and iPhone. LitLink routes LitPads audio to Discord, OBS, Zoom, or any other application. Together they provide a complete audio routing and soundboard solution for streamers and content creators.
</details>

---

## Download

**[Download LitLink.pkg](https://github.com/linguaholic/litlink-app/releases/latest/download/LitLink.pkg)** — macOS 14+ · Signed & notarized by Apple

Learn more at **[litpads.app/litlink](https://litpads.app/litlink)**

---

## License

LitLink is proprietary software. Free features are available at no cost. Pro features require a paid license. See [Terms of Service](https://litpads.app/terms) for details.
