# macOS-ContentCache-Statistic-viewer
Implementation for apple content cache statistics in home assistant using node-red an the cli tools for the build-in caching server

## Requirements for Caching-Server-Mac
- nmap
- Running node-red Instance
- enabled Caching Service

## Other Requirements
- Running Home Assistant Instance (Local or Network)

## Installation for Caching-Server-Mac
1. Open up your Browser and navigate to your Node-Red configuration website.
2. Install the 'node-red-contrib-home-assistant-websocket' - Nodes
3. Import the nodes from 'node-red/IMPORT_THIS.json'
4. Configure your HomeAssistant Instance in every Node. For this, you can create a access-token in your HomeAssistant instance. Open up your HomeAssistant instance in your Browser, navigate to your Profile and scroll down to the bottom. There you have the possiblity to create the Access-Token you need for node-red.
