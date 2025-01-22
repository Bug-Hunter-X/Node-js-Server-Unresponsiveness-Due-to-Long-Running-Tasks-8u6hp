# Node.js Server Unresponsiveness

This repository demonstrates a common issue in Node.js applications: server unresponsiveness caused by long-running tasks that block the event loop.  The `serverBug.js` file showcases a server that introduces a 5-second delay for each request, which will eventually lead to the server becoming unresponsive under heavy load.

The `serverBugSolution.js` file provides a solution using asynchronous operations to prevent blocking the event loop and maintain server responsiveness.