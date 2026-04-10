# WhisperMe

macOS menu bar app for voice-to-text using local AI.

## Download

[Latest Release](https://github.com/Ins0mn1aUA/WhisperMe-releases/releases/latest)

## Features

- Hold **Fn/Globe** key to record, release to transcribe and paste
- Local transcription via WhisperKit (OpenAI Whisper on Apple Silicon)
- Multiple Whisper models (Tiny to Large v3 Turbo)
- 100+ recognition languages with auto-detection
- 16 interface languages
- Favorite languages for quick access
- Transcription history (Cmd+Shift+H)
- Audio ducking during recording
- Auto-updates via Sparkle

## Requirements

- macOS 14.0+ (Sonoma)
- Apple Silicon (M1/M2/M3/M4)

## Installation

1. Download `.dmg` from [Releases](https://github.com/Ins0mn1aUA/WhisperMe-releases/releases)
2. Drag WhisperMe to Applications
3. Remove quarantine (required on macOS 15+):
   ```bash
   xattr -cr /Applications/WhisperMe.app
   ```
4. Grant **Microphone** and **Accessibility** permissions

## Permissions

- **Microphone** — for recording speech
- **Accessibility** — for Fn key capture and text pasting (System Settings → Privacy & Security → Accessibility)
