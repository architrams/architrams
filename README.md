# Stock AI Agent Web App

This project is a minimal static web application demonstrating an AI assistant for stock market and portfolio management. It includes:

- **Interactive 3D Page** – The home page renders a rotating 3D cube using [Three.js](https://threejs.org/) and provides an interface to query the OpenAI API about stocks or portfolios.
- **Real-time Learning Page** – A separate page fetches real-time stock prices for IBM using the Alpha Vantage demo API and updates every five seconds.

## Usage

1. Serve the `public/` directory with any static file server (e.g. `python -m http.server` or an extension in your editor).
2. Open `index.html` in a browser.
3. Provide your OpenAI API key and ask questions about stocks or portfolio management.
4. Navigate to **Real-time Stock Page** to watch live price updates.

> **Note:** API keys are entered directly in the browser for demonstration purposes only. For production use, route requests through a secure backend.

## Development

- No build step is required. The site uses CDN links for all libraries.
- Run `npm test` to execute a placeholder test script.

## License

MIT

