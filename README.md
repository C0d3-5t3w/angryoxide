
![Logo](death.png)

# AngryOxide

### A Rust WPA Attack tool.

This tool was developed as a way to learn rust, netlink, kernel sockets (and eBPF) all at once- with a focus on WiFi exploitation.

## Features

- Active attack engine used to retrieve relevent messages from Access Points.
- "Smart Attack" - considers attack status, AP state, and AP capabilities before blindly (brute-force) attacking.
- EAPOL Capture & 4-Way-Handshake validation using Nonce Correction, Replay Counter validation, and Temporal validation.
- PMKID collection and validation (non-zeroed).

## Screenshots

![Screenshot](wpoxide.png)


## Attack Engine

WIP state-based AP attack engine.

![Attack Engine Diagram](engine.png)
