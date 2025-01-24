# Proxy-Server

A simple Python-based proxy server with caching functionality. This server listens on a specified port, intercepts HTTP requests, and serves files from cache if available. If the file is not cached, it fetches it from the origin server, caches it, and then serves it to the client. It also supports blocking URLs from a blocklist. The application uses basic HTML and Python file handling to implement a functional cache proxy server.
