# Running the server
* run npm install, then run npm start
* then in another terminal window run ngrok http 3000 and copy the https url that looks something like this: https://f7333e87.ngrok.io. This is required because WebSockets require https.
* Open GoExpo and edit SocketClient.js to contain your ngrok url
