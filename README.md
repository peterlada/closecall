# Close Call

Historical adjusted closed daily prices built with Python 3.13.

## Features

- Modern Python 3.13
- UV package management

## Setup

### Installation

1. Create a virtual environment and install dependencies with UV

```bash
# Install UV if you don't have it already
curl -LsSf https://astral.sh/uv/install.sh | sh

uv install python

# Create a virtual environment and install dependencies
uv venv
source .venv/bin/activate  # On Windows, use: .venv\Scripts\activate
uv pip install -e ".[dev]"
```

## Usage

Run the application locally:

```bash
uv run main.py
```
