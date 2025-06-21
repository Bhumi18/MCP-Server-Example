# 🌦️ MCP Weather Server

This project implements a simple Model Context Protocol (MCP) server that provides weather data tools using the National Weather Service (NWS) API.

It includes two MCP tools:
- `get-alerts`: Get weather alerts for a U.S. state
- `get-forecast`: Get weather forecast for a specific latitude and longitude

## 🚀 Features

- Built using the `@modelcontextprotocol/sdk`
- Uses `zod` for input validation
- Communicates over `stdio` for integration with AI agents (e.g. Ember, Devin)
- Fetches real-time weather data from the U.S. National Weather Service

---

## 🛠️ Requirements

- Node.js (v18 or higher recommended)
- npm or yarn

---
