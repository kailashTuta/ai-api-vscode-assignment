# AI API VS Code Assignment

A simple Python API client sample project for calling AI endpoints, built as a minimal assignment template.

## Project Structure

- `src/`
  - `main.py`: CLI entrypoint and sample usage.
  - `api_client.py`: HTTP client code for interacting with the AI API.
  - `utils.py`: Utility helper functions.
- `requirements.txt`: Python dependencies.
- `README.md`: Project documentation.

## Setup

1. Create a Python virtual environment:
   ```bash
   python3 -m venv .venv
   source .venv/bin/activate
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Set your AI API key as an environment variable (example):
   ```bash
   export OPENAI_API_KEY="your_api_key"
   ```
2. Run the sample script:
   ```bash
   python src/main.py
   ```

## Development

- Add new API methods in `src/api_client.py`.
- Add helper functions in `src/utils.py`.
- Use `src/main.py` for quick demonstration and local testing.

## Notes

- This repository is intentionally small and focused on a simple API client demo.
- If your environment uses different paths, update `src/main.py` accordingly.
