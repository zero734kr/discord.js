# discord.js documentation files

This branch hosts the documentation JSON files used for https://discord.js.org/#/docs.
No manual commits should ever need to be done to this branch.

The class that sends voice packet data to the voice connection.\n
```js\n// Obtained using:\nvoiceChannel.join().then(connection => {\n  // You can play a file or a stream here:\n  const dispatcher = connection.play('/home/hydrabolt/audio.mp3');\n});\n```