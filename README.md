<p align="center">
  <img src="icon_512.png" alt="LitLink app icon" width="180" />
</p>

<h1 align="center">LitLink — Virtual Audio Cable for Mac</h1>

<p align="center">
  A free virtual audio driver for macOS that routes system audio and microphone input to any application.<br/>
  One-toggle setup, a free per-app volume mixer, no Audio MIDI Setup.
</p>

<p align="center">
  <a href="https://github.com/linguaholic/litlink-app/releases/latest"><strong>Download LitLink Free</strong></a>&nbsp;&nbsp;·&nbsp;&nbsp;
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

LitLink is a virtual audio driver for macOS with a companion app. It adds a virtual audio device, **LitLink Audio Bridge**, that any application (Discord, OBS, Zoom, QuickTime or any DAW) can use as its input to receive system audio, your microphone, or both.

Unlike BlackHole or other virtual audio cables that need manual Audio MIDI Setup configuration, LitLink sets everything up for you with a single toggle. It also adds the per-app volume mixer macOS never shipped.

---

## Features

### LitLink Free

Everything you need for everyday audio routing. Free, no account required, no time limit.

| Feature | Description |
|---------|-------------|
| **Per-App Volume Mixer** | A different volume for every app, mute apps individually, and a master fader, right from the menu bar. The mix plays through the output you already use. |
| **System Audio Passthrough** | Routes all system audio into LitLink Audio Bridge with one toggle. Creates the multi-output device for you, and can follow your Mac's output when you switch to headphones or AirPods. |
| **Mic Passthrough** | Mixes your microphone (USB, built-in, audio interface, or Bluetooth headsets like AirPods) into the same stream as system audio. No aggregate device needed. |
| **Recording** | Record whatever flows through LitLink Audio Bridge (mic, system audio or both) to a .wav file, no DAW needed. |
| **Menu Bar App** | Visual controls, live level meters and status, with the same controls in the menu bar. |
| **Persistence** | Your setup survives restarts and updates. |
| **Built-in Setup Guide** | Step-by-step setup for Discord, OBS, Zoom and other apps. |

### LitLink Pro: $3.99/month or $29 lifetime

For streamers, podcasters and musicians who need more than one thing going on.

| Feature | Description |
|---------|-------------|
| **Per-App Routing** | Send each app to its own LitLink track (8 tracks, each a separate input in OBS, Discord or your DAW) or straight to a different output device: music on the speakers while the call stays on your AirPods. |
| **Mix Mode** | Blend apps, mic and system audio into one mix, hear it live, and send that exact mix to your stream, recordings and calls. |
| **Mic Sends and Additional Inputs** | Your mic into any track at its own level, plus a second mic or an instrument with its own EQ. |
| **Volume Boost up to 400%** | Make quiet apps loud, with a limiter that keeps them clean. |
| **EQ, Limiter and AU Plugins** | Parametric EQ and limiter per app, on your mic and on the final mix, plus any Audio Unit effect. |
| **Separate-Tracks and Per-Track Recording** | Your mic, your apps and each track as separate files from one take, or Split L/R (mic left, apps right). |
| **Multi-Track Editor** | Stack a session's recordings, trim, fade, mix and export. |
| **Named Tracks and DAW-to-DAW Routing** | Your own track names in OBS, Discord and your DAW, and up to 8 tracks between two DAWs. |
| **7-Day Free Trial** | Start it in the app. No credit card required. |

---

## Quick Start

1. **Download** the latest [LitLink installer](https://github.com/linguaholic/litlink-app/releases/latest) and run it
2. **Open LitLink** from Applications
3. **Turn on System Audio Passthrough**, one click
4. **Select "LitLink Audio Bridge"** as the input device in Discord, OBS, Zoom or any app
5. **Optional:** turn on Mic Passthrough to mix your voice in

That's it. No Audio MIDI Setup, no multi-output device configuration, no clock settings.

---

## Use Cases

| Use Case | How |
|----------|-----|
| **Balance your apps' volumes** | Open the Per-App Volume tab or the menu bar and set each app's level (free) |
| **Share audio on Discord** | Turn on System Audio Passthrough, select LitLink Audio Bridge as the input in Discord's voice settings |
| **Capture system audio in OBS** | Add LitLink Audio Bridge as an audio input source in OBS |
| **Play audio in Zoom meetings** | Select LitLink Audio Bridge as your microphone in Zoom |
| **Record app audio** | Use LitLink's Record button, or choose LitLink Audio Bridge in QuickTime |
| **Route a soundboard to Discord or OBS** | Use [LitPads](https://litpads.app) for the soundboard and LitLink for routing |
| **Stream with per-app control** | LitLink Pro: game on its own track for OBS, music kept out of the call |
| **Record a podcast** | LitLink Pro: your mic, your guest's app and the mix as separate files from one take |

---

## LitLink vs BlackHole

| | LitLink Free | LitLink Pro | BlackHole |
|---|---|---|---|
| **Price** | Free | $3.99/month or $29 lifetime | Free (open source) |
| **Setup** | One toggle | One toggle | Manual Audio MIDI Setup |
| **Companion App** | Included | Included | Not included |
| **Per-App Volume** | Included | Included | Not included |
| **Mic Passthrough** | Built in | Built in | Not included |
| **Recording** | Built in | Per track and separate files | Not included |
| **Per-App Routing** | Not included | 8 tracks or any output device | Not included |
| **EQ and Limiter** | Not included | Per app, mic and mix | Not included |

---

## Technical Specifications

| Spec | Value |
|------|-------|
| **Driver Type** | Core Audio HAL plug-in (runs inside macOS's audio service, no kernel extension) |
| **Audio Format** | 32-bit float, stereo |
| **Sample Rates** | 44.1 kHz, 48 kHz, 96 kHz |
| **Architecture** | Universal (Apple Silicon and Intel) |
| **Minimum macOS** | 14.0 Sonoma (Pro per-app routing needs 14.2) |
| **Installer** | Signed with Developer ID, notarized by Apple |
| **Installer Size** | About 8.5 MB |

---

## Frequently Asked Questions

<details>
<summary><strong>Is LitLink really free?</strong></summary>
<br/>
Yes. LitLink Free includes the per-app volume mixer, System Audio Passthrough, Mic Passthrough, recording, the menu bar app and the setup guide. No trial period, no time limit, no account required. These features stay free.
</details>

<details>
<summary><strong>How do I get LitLink Pro?</strong></summary>
<br/>
Install LitLink Free first. In the app, open the Pro section and start the 7-day free trial (no card needed), or click Buy Pro and choose monthly ($3.99) or lifetime ($29). After purchase you get a transaction ID by email: enter it in the app and Pro unlocks instantly, no reinstall needed.
</details>

<details>
<summary><strong>Does LitLink work with Apple Silicon and Intel Macs?</strong></summary>
<br/>
Yes. The app and the driver are universal binaries and run natively on Apple Silicon and Intel Macs, without Rosetta.
</details>

<details>
<summary><strong>Can I use AirPods or other Bluetooth headsets as my mic?</strong></summary>
<br/>
Yes. LitLink converts their low sample rate itself. While their mic is in use, macOS plays Bluetooth headsets at call quality, the same as in any calling app.
</details>

<details>
<summary><strong>Is LitLink safe to install?</strong></summary>
<br/>
LitLink is signed with a Developer ID certificate and notarized by Apple, and macOS Gatekeeper checks the signature before installation. The installer places the audio driver in the standard system audio plug-in folder and the app in your Applications folder.
</details>

<details>
<summary><strong>Does LitLink add latency?</strong></summary>
<br/>
System Audio Passthrough adds no noticeable delay. Mic Passthrough and per-app routing pass through a short buffer that LitLink keeps small, well within what calls and streams tolerate. If you ever need numbers, Export Diagnostics in the app reports the measured delay.
</details>

<details>
<summary><strong>How do I uninstall LitLink?</strong></summary>
<br/>
Open LitLink and click Uninstall Driver in the Driver Status card at the bottom of the sidebar. LitLink turns off passthrough, removes its multi-output device, restores your original output and removes the driver. Then delete LitLink from Applications.
</details>

<details>
<summary><strong>Which apps work with LitLink?</strong></summary>
<br/>
Any app that accepts audio input on macOS: Discord, OBS, Zoom, Google Meet, Microsoft Teams, QuickTime, GarageBand, Logic Pro, Ableton Live, Audacity and other DAWs and recording tools.
</details>

<details>
<summary><strong>Why doesn't an app show up in the per-app list?</strong></summary>
<br/>
Apps appear once they play audio. Start playback in the app and it shows up; you can also add and pin apps so they stay in the list.
</details>

<details>
<summary><strong>Can I control or route a single web app?</strong></summary>
<br/>
Yes, with Safari: open the site in Safari and choose File > Add to Dock. The web app then appears in LitLink as its own app with its own volume, and with Pro its own routing. Web apps installed from Chrome or Edge play their sound through the browser together with all its tabs, so they can't be separated from it.
</details>

<details>
<summary><strong>Can I use LitLink with LitPads?</strong></summary>
<br/>
Yes. LitPads is a custom soundboard app for Mac, iPad and iPhone. LitLink routes LitPads audio to Discord, OBS, Zoom or any other app.
</details>

---

## Download

**[Download the latest LitLink installer](https://github.com/linguaholic/litlink-app/releases/latest)** · macOS 14+ · about 8.5 MB · Signed & notarized by Apple

Looking for a specific version? Every release is archived on the **[releases page](https://github.com/linguaholic/litlink-app/releases)**.

Learn more at **[litpads.app/litlink](https://litpads.app/litlink)**

---

## License

LitLink is proprietary software. Free features are available at no cost. Pro features require a paid license. See [Terms of Service](https://litpads.app/terms) for details.
