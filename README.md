# Ghost Prompt CTF

A prompt injection challenge game built with Large Language Models (LLMs). Test your skills in extracting secret passwords from an AI through clever prompt engineering.

## Overview

This project implements a Capture The Flag (CTF) style game where players attempt to bypass an LLM's security measures to reveal hidden passwords. The game progresses through multiple levels of increasing difficulty, each with a different AI persona designed to protect the secret.

## Features

- **Multi-level Challenge**: 3 progressive levels with different AI personalities
- **Web Interface**: Streamlit-based chat application
- **LLM Integration**: Uses Qwen2.5-1.5B-Instruct model
- **Public Hosting**: Ngrok integration for easy deployment

## Setup

1. Install dependencies:
   ```bash
   pip install transformers accelerate bitsandbytes streamlit pyngrok
   ```

2. Run the notebook to set up and deploy the game.

## How to Play

1. Access the web interface (deployed via Ngrok)
2. Chat with the AI and try to extract the secret password
3. Use prompt injection techniques to bypass security
4. Advance through levels by successfully revealing passwords

## Educational Purpose

This project demonstrates LLM vulnerabilities to prompt injection attacks and serves as a learning tool for AI security and prompt engineering.

## License

[Add your license here]