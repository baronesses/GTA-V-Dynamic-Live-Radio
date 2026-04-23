# 📻 GTA V Dynamic Live Radio Server

![Status](https://img.shields.io/badge/Status-Beta-orange)
![Category](https://img.shields.io/badge/Category-Audio_Streaming_%26_Backend-blueviolet)

## 📌 Overview
A custom backend streaming server designed to recreate the authentic GTA V radio experience in real life. Instead of playing static audio files, this engine dynamically stitches together extracted game audio fragments (songs, DJ talks, commercials, news) to generate continuous, non-repeating live radio broadcasts. 

Built as a headless API, it simultaneously streams multiple stations, ensuring that every 1-2 hour cycle is completely unique. 

## ✨ Key Features (Backend Core)
* 🔄 **Procedural Audio Assembly:** Dynamically rebuilds radio cycles on the fly. The chance of hearing the exact same sequence of songs and host interactions is practically zero.
* 📡 **Concurrent Live Streaming:** Runs multiple independent radio streams (Los Santos Rock, Non-Stop-Pop, West Coast Classics, etc.) simultaneously, perfectly mimicking live FM broadcasting.
* 🛠️ **Lightweight Headless API:** Powered by Flask (utilized as a fast API layer) to serve audio streams directly to any client.
* 🎛️ **Diagnostic Dashboard:** A built-in web UI for real-time monitoring of all active audio streams and current track states.

## 🚀 Roadmap
* 📱 **Mobile Client:** Dedicated application for iOS/Android to tune into the live streams.
* 🚗 **In-Car Integration:** Android Auto / Apple CarPlay compatibility to seamlessly integrate the live radio into real-world driving.
* 🎙️ **Custom AI Host (Experimental):** Integrating AI-generated news or custom host voiceovers between tracks.

## 🛠️ Tech Stack
* **Core Language:** Python
* **Web Framework:** Flask (RESTful API / Debug UI)
* **Frontend (Debug):** HTML5 Audio API / Vanilla JS

---
*Note: This is a non-commercial project created for backend architecture practice. All audio assets belong to their respective copyright holders.*
