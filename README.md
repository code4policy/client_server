# Client-Server Demo

A simple demonstration of client-server architecture where one computer becomes a web server that others can access.

## For Server (Presenter)

1. Clone this repository:
```bash
git clone https://github.com/code4policy/client_server.git
cd client_server
```

2. Install serve:
```bash
npm install -g serve
```

3. Start your computer as a web server:
```bash
serve
```
This command turns your computer into a web server that:
- Serves the index.html file in this repository
- Listens for incoming connections on port 3000
- Can be accessed by other computers on your network


## For Clients (Students)
1. Get the server's IP address from the presenter
2. Open your web browser
3. Navigate to: `http://PRESENTER_IP:3000`
   You are now making a request to your classmate's computer!

**NOTE: Make sure to be on the same wifi**

## Common Issues
1. Can't connect to server:
   - Verify you're on the same network 
   - Check if firewall is blocking connections
   - Confirm IP address and port

## Network Requirements
- All participants must be on the same local network
- Some corporate/university networks may block peer-to-peer connections
- Public WiFi might restrict device-to-device communication
