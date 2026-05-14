# stackchan-edge-ai-lab

Conversational Edge AI experiments using StackChan, Arduino UNO Q, OpenAI and Embedded Linux.

---

# Overview

This project documents, step-by-step, the creation of a personal conversational AI laboratory focused on:

* Voice AI
* Edge AI
* Embedded systems
* ESP32-S3
* OpenAI integration
* PT-BR and English conversations
* Hybrid AI architectures
* Conversational IoT
* Human-machine interaction

The objective is NOT only to build a robot.

The main goal is to create a practical and didactic experimental platform for:

* technical studies
* engineering productivity
* conversational interfaces
* bilingual interaction (Portuguese/English)
* Edge AI experimentation
* future IoT integrations

---

# Main Hardware

## StackChan

Official documentation:

[https://docs.m5stack.com/en/StackChan](https://docs.m5stack.com/en/StackChan)

StackChan is an open-source desktop AI robot based on ESP32-S3.

Main features:

* ESP32-S3
* display
* dual microphones
* speaker
* servos
* Wi-Fi/Bluetooth
* conversational interaction
* open-source ecosystem

The StackChan will be used as:

* conversational terminal
* physical voice interface
* AI interaction device
* experimental embodied AI platform

---

## Arduino UNO Q

Official documentation:

[https://www.arduino.cc/product-uno-q](https://www.arduino.cc/product-uno-q)

The Arduino UNO Q is a modern hybrid embedded platform combining:

* Linux system
* Qualcomm processing
* embedded AI acceleration
* real-time MCU
* Wi-Fi/Bluetooth
* multimedia support

The UNO Q will initially act as:

* AI backend
* OpenAI gateway
* conversational orchestration server
* experimentation platform

---

# Initial Architecture

```text
StackChan (ESP32-S3)
        ↓
Arduino UNO Q
        ↓
OpenAI APIs
```

The initial objective is to keep the architecture SIMPLE.

At the beginning, the focus will be:

* voice quality
* low latency
* PT-BR support
* English support
* conversational experience
* streaming
* stability

---

# Why This Project?

The project was created to explore:

* Edge AI
* Voice AI
* Hybrid AI
* Conversational systems
* Embedded Linux
* ESP32 systems
* Human-computer interaction
* Technical productivity using voice

Example use cases:

* asking technical questions by voice
* studying embedded systems
* discussing firmware architecture
* practicing technical English
* interacting hands-free during electronics work

---

# Project Philosophy

This repository follows a VERY important principle:

## Start simple.

Instead of immediately modifying everything, the project will first:

1. Test the original StackChan firmware
2. Document the manufacturer experience
3. Measure limitations and strengths
4. Create a technical baseline
5. Evolve gradually

This approach improves:

* reproducibility
* learning quality
* debugging
* documentation quality
* future comparisons

---

# Development Phases

# Phase 0 — Project Preparation

Current phase.

Objectives:

* prepare GitHub repository
* prepare documentation
* prepare Arduino UNO Q
* study OpenAI APIs
* define architecture

---

# Phase 1 — Original StackChan Evaluation

IMPORTANT:

The StackChan will FIRST be tested exactly as delivered by the manufacturer.

This phase will document:

* unboxing
* firmware version
* first boot
* Wi-Fi setup
* voice quality
* PT-BR tests
* English tests
* latency
* speaker quality
* microphone quality
* conversation quality
* limitations

No major modifications at first.

The goal is to understand the original platform before customization.

---

# Phase 2 — OpenAI Integration

Goals:

* connect StackChan to OpenAI
* evaluate conversational quality
* test bilingual interaction
* evaluate latency
* compare streaming approaches

Planned technologies:

* Python
* FastAPI
* WebSocket
* OpenAI SDK

---

# Phase 3 — UNO Q AI Backend

Goals:

* conversational memory
* context persistence
* orchestration layer
* prompt management
* bilingual assistant
* future local AI experiments

---

# Phase 4 — Hybrid AI and IoT

Future phase.

Possible experiments:

* MQTT
* sensors
* automation
* Home Assistant
* distributed IoT
* local AI models
* hybrid cloud/local inference

---

# Initial Repository Structure

```text
stackchan-edge-ai-lab/
├── README.md
├── docs/
│   ├── 00-overview/
│   ├── 01-unboxing/
│   ├── 02-stock-firmware/
│   ├── 03-initial-tests/
│   ├── 04-ptbr-tests/
│   ├── 05-english-tests/
│   ├── 06-openai-integration/
│   ├── 07-unoq-backend/
│   ├── 08-hybrid-ai/
│   └── future/
├── backend/
├── firmware/
├── hardware/
├── voice/
└── experiments/
```

---

# Initial Technical Goals

## Voice Interaction

* PT-BR support
* English support
* low latency
* natural interaction

---

## Educational Goals

* improve technical English
* study embedded systems
* study Edge AI
* document experiments publicly

---

## Engineering Goals

* modular architecture
* reproducible environment
* scalable design
* practical experimentation

---

# Technologies Planned

## Embedded Systems

* ESP32-S3
* Embedded Linux
* Arduino ecosystem

---

## Software

* Python
* FastAPI
* WebSocket
* asyncio
* OpenAI SDK
* Git/GitHub

---

## AI

* OpenAI APIs
* voice AI
* streaming interaction
* future hybrid AI experiments

---

# Important Notes

This project is intentionally incremental.

The priority is:

1. stability
2. voice quality
3. simplicity
4. documentation quality
5. learning

The project is NOT trying to build a complex robotics platform immediately.

The main focus is:

* conversational interaction
* technical productivity
* experimentation
* educational value

---

# GitHub Setup

## Create repository locally

```bash
git init
```

---

## Add files

```bash
git add .
```

---

## First commit

```bash
git commit -m "Initial project structure and README"
```

---

## Connect GitHub repository

```bash
git remote add origin https://github.com/YOUR_USER/stackchan-edge-ai-lab.git
```

---

## Push repository

```bash
git branch -M main
git push -u origin main
```

---

# Suggested First Tasks

## Before StackChan Arrival

* Prepare Arduino UNO Q
* Install Python environment
* Configure Git and SSH
* Test OpenAI APIs
* Organize repository structure
* Plan documentation

---

# Future Ideas

Possible future directions:

* local AI inference
* voice streaming optimization
* wake-word detection
* embodied AI experiments
* sensor integrations
* Home Assistant integration
* bilingual engineering assistant
* Edge AI benchmarks

---

# License

Project currently under evaluation.

Possible future options:

* MIT
* Apache 2.0

---

# Final Notes

This repository aims to become:

* a learning platform
* a practical engineering reference
* a conversational Edge AI laboratory
* a bilingual technical documentation project

The project will evolve incrementally and be documented step-by-step.
