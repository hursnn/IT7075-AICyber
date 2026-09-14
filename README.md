 # IT7075 Applied AI for Cybersecurity

This repository contains my coursework and environment setup for IT7075 Applied AI for Cybersecurity.

## Python Environment

A Python virtual environment (`.venv`) is used to isolate project dependencies. Required Python packages are listed in `requirements.txt`.

## LLM API

The project uses the Gemini API for programmatic LLM access.

- Local development: API credentials are loaded from a `.env` file.
- Google Colab: API credentials are loaded using Colab Secrets.
- API credentials are excluded from Git version control.

## Security

The `.env` file and `.venv/` directory are excluded using `.gitignore` to prevent credentials and local environment files from being committed.