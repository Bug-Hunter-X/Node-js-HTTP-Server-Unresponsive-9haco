# Node.js HTTP Server Unresponsive

This repository demonstrates a common issue in Node.js where an HTTP server appears to start successfully but fails to respond to incoming requests. The bug is subtle and may be missed by developers unfamiliar with asynchronous programming in Node.js.

## Bug Description

The provided `server.js` file creates a basic HTTP server. However, despite starting without errors, the server remains unresponsive to requests. This is due to a common misunderstanding of how Node.js handles asynchronous operations.

## Bug Solution

The solution (`serverSolution.js`) is provided, demonstrating the proper way to handle the `request` event and respond to the client.