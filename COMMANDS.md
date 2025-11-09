# Quick Commands Reference

## Installation

```bash
npm install
```

## Running the Application

### Start Server (Production)
```bash
npm start
```

### Start Server (Development with auto-restart)
```bash
npm run dev
```

### Start Server on Custom Port
```bash
PORT=3001 npm start
```

## Access the Application

Once the server is running, open your browser and navigate to:
```
http://localhost:3000
```

## Testing with Multiple Users

1. Start the server: `npm start`
2. Open `http://localhost:3000` in your browser
3. Enter a name and optionally a room ID
4. Click "Join Room"
5. Open another browser window/tab to the same URL
6. Enter a different name and the same room ID
7. Start drawing - you should see real-time synchronization!

## Troubleshooting

### Port Already in Use
```bash
# Windows PowerShell
$env:PORT=3001; npm start

# Windows CMD
set PORT=3001 && npm start

# Linux/Mac
PORT=3001 npm start
```

### Reinstall Dependencies
```bash
# Windows
rmdir /s node_modules
npm install

# Linux/Mac
rm -rf node_modules
npm install
```

### Check Node.js Version
```bash
node --version
```
Should be v16 or higher.

