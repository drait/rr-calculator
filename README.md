# Trade Position Size Calculator

This project provides a standalone HTML page for calculating recommended trade size and take-profit targets.

## Prerequisites
No build tools or dependencies are required. Any modern web browser can open the calculator locally.

## Running the App
You have two easy options:

### Option 1: Open the file directly
1. Locate `index.html` in the project root.
2. Double-click the file or open it from your browser (e.g., drag it into a new tab).

### Option 2: Use a lightweight local server (recommended for testing responsive layouts)
1. Start a simple HTTP server from the project directory:
   ```bash
   python3 -m http.server 8000
   ```
2. Visit [http://localhost:8000/index.html](http://localhost:8000/index.html) in your browser.

Either approach will load the calculator so you can input trade parameters and view the computed results. An active internet connection is required for fetching the latest ticker price data (queried from Yahoo Finance).
