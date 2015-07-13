# webrtc-4-qos
WebRTC code used for Public Safety Communications Research

## Getting Started
I will describe the setup of my development environment on OSX:

1. Download the .zip or clone this repository onto your local machine.
2. Set up the Apache server on your Mac, here is what I used: [Apache server setup for OSX](http://getgrav.org/blog/mac-os-x-apache-setup-multiple-php-versions)
3. Go to where you downloaded or cloned the code. `cd` into the `webrtc-4-qos` directory, then select all the files and folders in this directory, copy them and then paste directly into the `Sites` folder you created when setting up the Apache server. If you `cd` into the `Sites` folder you should see `index.html`, `serve_index.js`, `twoWayVideoWithChat.html`, `_assets` folder, `css` folder etc.
4. Download [Node.js](https://nodejs.org/).
5. `cd` into your `Sites` folder and type: 
   + `npm install socket.io`
   + `npm install node-static`
   + `npm install websocket`
   + `npm install express`
   

## How to run the code
   
