## Socket.io Version Update

To resolve the donation message that appears when connecting to the editor, we've updated the socket.io-client version from 4.6.1 to 4.5.4. This version doesn't display the donation message while maintaining full compatibility with our socket.io server version.

After this change, please run:
```bash
cd frontend
npm install
```

This will update your node_modules with the new socket.io-client version and remove the donation message.