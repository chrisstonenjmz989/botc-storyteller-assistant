# BOTC AI Storyteller Assistant v2026 - board game assistant 2026

> BOTC AI Storyteller Assistant v2026 is a local-first browser tool for Blood on the Clocktower storytellers. Use it to organize rooms, assign roles, guide game phases, and inspect session history through a web interface.

[![Platform](https://img.shields.io/badge/Platform-web-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2026-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/chrisstonenjmz989/botc-storyteller-assistant?style=flat-square)](https://github.com/chrisstonenjmz989/botc-storyteller-assistant)

---

<p align="center">
  <a href="https://chrisstonenjmz989.github.io/botc-storyteller-assistant/">
    <img src="https://img.shields.io/badge/Download-BOTC%20AI%20Storyteller%20Assistant%20Latest-brightgreen?style=for-the-badge" alt="Download BOTC AI Storyteller Assistant">
  </a>
</p>

> **[Download BOTC AI Storyteller Assistant v2026](https://chrisstonenjmz989.github.io/botc-storyteller-assistant/)**

---

[Download Latest Build](https://chrisstonenjmz989.github.io/botc-storyteller-assistant/)

---

## What Is BOTC AI Storyteller Assistant?

BOTC AI Storyteller Assistant is an unofficial, fan-created browser application for Blood on the Clocktower. It brings table preparation and game administration into a single interface, with a local-first design suitable for in-person sessions and LAN access.

Storytellers can use the app to arrange seating, deliver identities, handle night actions, record nominations and outcomes, and follow the game from phase to phase without depending on a complete external service. The application also preserves game history, making it possible to revisit earlier events and track the session state.

---

## Key Capabilities

- Set up rooms and arrange players around the table
- Select a script and produce candidates for the initial setup
- Deliver each player's identity privately
- Manage night submissions and inspect available candidates
- Record daytime nominations, votes, and executions
- Browse previous actions through game history and review tools
- Play through a browser locally or across a LAN
- Require storyteller confirmation before significant state changes

---

## Installation

Download or clone the repository, then open the web application in a browser:

- `git clone https://github.com/chrisstonenjmz989/botc-storyteller-assistant.git
- `cd botc-ai-storyteller-public`

For a local installation, use any static web server to serve the directory and visit it with a modern browser. When using the app over a LAN, other devices should connect through the host machine on the same network.

---

## Getting Started

1. Launch the browser app from the host device.
2. Create a room and enter the players.
3. Select the desired script and inspect the suggested setup candidates.
4. Provide identities privately to the individual players.
5. Record night submissions, daytime nominations, votes, and executions with the relevant tools.
6. Consult the session history while the game continues.

A normal session generally follows this sequence:

- Create a room
- Seat the players
- Verify the setup
- Conduct night actions
- Record nominations and votes
- Consult the timeline whenever necessary

---

## Configuration and Hosting

The browser session and active room determine most of the application's behavior. For self-hosted deployments, the main considerations are the method used to serve the static files and whether players access the app through localhost or over a LAN.

A basic deployment can be organized as follows:

- **Host location:** Local computer or LAN server
- **Access method:** Web browser
- **State handling:** Room controls within the application
- **Administrative flow:** Storyteller approval before important game state updates

---

## Requirements

- A current web browser
- A device capable of hosting or reaching the app over a local network for LAN sessions
- A static file server or equivalent method for local deployment
- Sufficient storage for the application files and browser-held session data

---

## Frequently Asked Questions

**What game is the application for?**  
It is designed for Blood on the Clocktower and its storyteller-oriented game management process.

**Can I use it without an internet connection?**  
Yes. It follows a local-first model and supports browser access over a local network.

**Where does the application keep its settings?**  
Room state and settings are handled through the browser workflow, with the exact behavior depending on the hosting and access setup.

**How can I get the newest version?**  
Pull the latest repository changes, or update the deployed installation with the newest release files.

**What if the app fails to load?**  
Confirm that you are using a modern browser, reload the page, and make sure the files are being served properly by the local or LAN host.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
