# Sandbox Environment

## Overview
This is a sandbox environment to learn how to integrate Cursor, GitHub, and Replit. The project was imported from GitHub and set up with a basic static website to demonstrate a working Replit environment.

## Project Structure
- `index.html` - Main landing page with styled content
- `server.js` - Simple Node.js HTTP server for development and production

## Technology Stack
- **Runtime**: Node.js 20
- **Frontend**: Static HTML/CSS
- **Server**: Node.js HTTP server

## Development
The project runs a simple HTTP server on port 5000 that serves static files. The server is configured to:
- Listen on `0.0.0.0:5000` for Replit compatibility
- Serve the `index.html` file by default
- Disable caching to ensure changes are immediately visible

## Deployment
The project is configured for autoscale deployment using `node server.js` as the run command.

## Setup Date
- Initial setup: December 7, 2025
- Imported from: GitHub
