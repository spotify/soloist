# Spotify Soloist

A new headless Spotify client for terminal-based and DIY setups.

Spotify Soloist is a lightweight, command-line Spotify Connect receiver for Linux, macOS, and Windows. Install it on a Raspberry Pi, a home server, any Linux box, or your Mac or PC, and it shows up in your Spotify app as a Connect device, ready to play. It is built on the same playback engine as the other Spotify apps.

Read the full announcement on the [Spotify for Developers blog](https://developer.spotify.com/blog/2026-08-13-introducing-spotify-soloist). 

## Features

* Music, podcasts, and audiobooks: the whole catalog, streaming into your custom setup  
* Spotify Connect: control playback from your phone or desktop  
* Local WebSocket API: playback control, real-time events, and queue access for building your own DIY integrations  
* Jam: listen together with your family and friends  
* Loudness normalization with peak limiting  
* Smart Shuffle and Autoplay to keep the music flowing  
* Lossless audio: up to 24-bit/44.1 kHz (Premium)  
* Crossfade and automix for smooth transitions between tracks (Premium)

## Requirements

* One of:  
  * A Raspberry Pi or any other Linux device on ARMv7, AArch64, or x86\_64, with PipeWire (or PulseAudio) for audio output  
  * An Apple Silicon Mac running macOS 13 or newer  
  * An x86\_64 Windows PC  
* A Premium account is needed to set up Spotify Soloist, but once it’s running both Free and Premium users can connect. Premium unlocks lossless audio and mixing  
* A [Spotify for Developers](https://developer.spotify.com) account, used to download Spotify Soloist and issue your device credential.

## Install & Getting Started

Read the full [Getting Started instructions](https://developer.spotify.com/documentation/soloist/tutorials/getting-started) on Spotify for Developers.

## WebSocket API

Spotify Soloist runs a local WebSocket server for integrations. It accepts playback commands (play, pause, seek, volume, shuffle, repeat, add to queue), emits real-time playback events, and exposes the play queue with full track metadata. If you are building a now-playing display, a hardware controller, or a home automation hook, start here: [WebSocket API](https://developer.spotify.com/documentation/soloist/reference/websocket-api)

## Feedback

Questions and general feedback: [the Soloist thread](https://community.spotify.com/t5/Blog-Prep/Spotify-Soloist-a-new-terminal-based-player-for-headless-and-DIY/ba-p/7529090) on the Spotify Community forum. Bug reports: open an issue on this repository.
