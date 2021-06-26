# Acacia – The Node.js Proxy Server

Acacia is the Node.js proxy server. Entirely written in Node.js, it supports reverse proxy, static file serving, PHP server via PHP-FPM (FastCGI), DNS proxy, load balancing, Let’s Encrypt automatic free SSL certificates, pathname rewriting, changing origin, custom headers, path mounting and much much more! Also, it supports WebSockets and can run WordPress.


## Features
Acacia offers the following features:
* Listens on any port of choice, either with or without SSL. By default, 80 and 443.
* Hostname / IP matching & default hostname.
* Hostname / IP aliasing (serve same content as another configured hostname, without redirecting).
* Path regex matching.
* SSL certificates, manual or provided by Let’s Encrypt. Let’s Encrypt certificates require port 80 to be publicly exposed, but provide automatic renewal.
* Hostname redirects with matching port and protocol.
* Redirects, both temporary and permanent.
* Reverse proxy.
* Static file serving from a specified location.
* SSL redirect to 443.
* Path rewrite when proxying requests.
* Change origin feature to forward or not forward the hostname to the target.
* WebSocket reverse proxying.
* Mount static directories on a specific path.
* Balance load by sequentially proxying to different targets.
* Log everything to file.
* DNS proxy.
* PHP server via PHP-FPM (FastCGI).
* WordPress support.
* WordPress permalinks supported.
