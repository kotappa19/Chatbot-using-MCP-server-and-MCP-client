# MCP Weather Server and Client

This project contains both an MCP (Model Context Protocol) server and client for weather data.

## Server

The server (`server.py`) provides weather-related tools:
- `get_alerts(state)`: Get weather alerts for a US state
- `get_forecast(latitude, longitude)`: Get weather forecast for a location

## Client

The client (`client.py`) connects to the MCP server and uses Claude AI to process queries and execute tools.

## Setup

1. Install dependencies:
```bash
uv sync
```

2. Create a `.env` file with your Anthropic API key:
```
ANTHROPIC_API_KEY=your_key_here
```

3. Run the client:
```bash
python client.py
```

