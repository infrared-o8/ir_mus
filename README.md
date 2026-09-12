# Infrared Music

The project had began as a personal tool, and a work in progress.

[![Latest Release](https://img.shields.io/github/v/release/infrared-o8/ir_mus?color=00FF66&label=RELEASE&logo=android)](https://github.com/infrared-o8/ir_mus/releases)
[![VirusTotal Scan](https://img.shields.io/badge/VirusTotal-Clean%200%2F61-brightgreen?logo=virustotal)](https://www.virustotal.com/gui/file/f42da283961443a6e8fe859ebc1ddd4016f11af3d03d9b86b9b3ffd2a2ab5588?nocache=1)

</div>

---

## Video Demonstration
<div align="center">
  <a href="https://www.youtube.com/watch?v=YJoHNKigPSs">
    <img src="https://img.youtube.com/vi/YJoHNKigPSs/maxresdefault.jpg" alt="Watch Full Walkthrough" width="85%"/>
    <br/>
    <b>▶ Watch Full 4-Minute Technical Walkthrough & Web Uplink Demo</b>
  </a>
</div>

---

## Feature Showcases

<div align="center">
  <table>
    <tr>
      <td align="center" width="50%">
        <b>Ktor Browser Uplink (Background Playback)</b><br/><br/>
        <img src="docs/demos/ktor_uplink_demo.gif" alt="Ktor Uplink Demo" width="360"/>
        <br/><br/>
        <i>Host an in-browser streaming player directly on your PC over LAN with 0 cloud accounts.</i>
      </td>
      <td align="center" width="50%">
        <b>AGSL Fluid Mesh & Visual Kinetics</b><br/><br/>
        <img src="docs/demos/visualizer_mesh_demo.gif" alt="AGSL Shaders Demo" width="360"/>
        <br/><br/>
        <i>Real-time Simplex noise and discrete node canvas rendering responsive to transient audio.</i>
      </td>
      <td align="center" width="50%">
        <b>Reactive Song Art Colors</b><br/><br/>
        <img src="docs/demos/audio_color.gif" alt="Song Art Colors" width="360"/>
        <br/><br/>
        <i>Displaying how the background audio reactor engine dynamically changes with each song according their album art.</i>
      </td>
    </tr>
  </table>
</div>

---

## Static Previews

<div align="center">
  <table>
    <tr>
      <td align="center" width="33%">
        <b>Library</b><br/><br/>
        <img src="docs/screenshots/library.png" alt="Library Screen" width="240"/>
      </td>
      <td align="center" width="33%">
        <b>Web Interface</b><br/><br/>
        <img src="docs/screenshots/web_uplink.png" alt="Ktor Web Client" width="240"/>
      </td>
      <td align="center" width="33%">
        <b>Now Playing</b><br/><br/>
        <img src="docs/screenshots/now_playing.png" alt="Now Playing" width="240"/>
      </td>
    </tr>
    <tr>
      <td align="center" width="33%">
        <b>Search</b><br/><br/>
        <img src="docs/screenshots/search.png" alt="Search Screen" width="240"/>
      </td>
      <td align="center" width="33%">
        <b>Home Page</b><br/><br/>
        <img src="docs/screenshots/home.png" alt="Home Page" width="240"/>
      </td>
      <td align="center" width="33%">
        <b>Settings</b><br/><br/>
        <img src="docs/screenshots/settings.png" alt="Settings Screen" width="240"/>
      </td>
    </tr>
  </table>
</div>

---

## What Problem This Solves

This was developed to allow direct music downloads and local network streaming without relying on third-party web tools, cloud lock-in, or ad-riddled download portals.

## Core Capabilities

* **Ktor Wi-Fi Uplink & Hero Player:** Host a local HTTP streaming server on port `:8080` straight from your Android device. Streams music directly to desktop browsers with full background playback support while your phone screen is off.
* **AGSL Shaders & Fluid Kinetics:** Procedural Simplex noise field and configurable floating glow orbs syncing dynamically to low-frequency audio transients.
* **Discord Rich Presence:** Real-time playback status synchronization to Discord desktop via a local IPC daemon.
* **Declarative Provider Dispatcher:** Multi-platform metadata and audio resolution with automated endpoint health failover.
* **Hardware-Inspired Scrubber:** Micro-wire interpolated 60 FPS scrubber with zero-latency position updates.
* **Network & Power Controls:** Strict Wi-Fi restrictions, auto-throttle under low battery, and charge-only download safeguards.
* **Auto-Updater:** Direct release checks against GitHub Releases. (somewhat broken at the moment, Im working on fixing it. Until this is fixed, please download the latest APK files from Releases)

## Download

You can download the latest release APK directly from [GitHub Releases](https://github.com/infrared-o8/ir_mus/releases).

## Project Status

The app is under active development. Some modules (advanced audio DSP parameters, theme recoloring, and full accessibility profiles) are still evolving.

Bug reports, feature suggestions, and pull requests are welcome via GitHub Issues or contact channels below:

* **Email:** infraredo979@gmail.com
* **Telegram:** [@infr466](https://t.me/infr466)
* **WhatsApp:** +91 70126 38570 *(Available for early tester codes)*
