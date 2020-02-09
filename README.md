Running the server
cd into the backend directory and run yarn or npm install, then run yarn start
Install ngrok and run ngrok http 3000 and copy the https url that looks something like this https://f7333e87.ngrok.io. This is required because WebSockets require https.
Open app/main.js and change the SocketEndpoint at the top of the file to point to your endpoint.