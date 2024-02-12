# CORS-Anywhere Proxy

## Description

Provides a Node.js-based CORS-Anywhere proxy server to bypass browser CORS restrictions for web requests.

## Installation

### Prerequisites:
 - Node.js and npm.
### Clone
```git clone https://github.com/leonsuv/cors-proxy.git```
### Install
```cd cors-anywhere-proxy && npm install```

## Usage
### Set environment variables (optional):
```
HOST='0.0.0.0'
PORT=8080
```
### Start:
```node server.js```
### Proxy requests:
Prepend the CORS-Anywhere URL to your target URL:
```http://localhost:8080/https://www.example.com```

## Configuration
Edit options in server.js for whitelisting origins, headers, etc.

## License
[MIT License](LICENSE.md)
