# GrokSync

Sync Grok's code and commands to GitHub with a tap.

## What It Does
- Extracts code blocks and commands from Grok's responses.
- Push code to GitHub (e.g., `Cargo.toml`, Rust files).
- Execute commands (e.g., create issues) via GitHub API.

## How to Use
1. Open [GrokSync](https://genie-robotics.github.io/groksync).
2. Enter your GitHub PAT (fine-grained, with `contents`, `issues` permissions).
3. Paste Grok's response.
4. Tap "Extract Code & Commands".
5. Review and tap "Push to GitHub" or "Execute".

## Setup
- Host on GitHub Pages or run locally.
- Generate a GitHub PAT with minimal scopes for your repo.

## License
MIT License
