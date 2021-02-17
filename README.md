## Jitsi Meet Electron app loader

Proof-of-concept landing page to load a [Jitsi](https://meet.jit.si/) room 
in the [Jitsi Meet Electron](https://github.com/jitsi/jitsi-meet-electron) app if installed. 

Falls back to providing a link to room in the browser instead.

Demo: https://s3.eu-west-2.amazonaws.com/stuff.shawnchin/jitsiPOC/index.html?room=JitsiElectronLoader (change the `room` 
param to default to a different room, or drop the param to load the main page.)


_**Disclaimer:** This is not fool-proof, and the detection of load success is know to have false positives and false 
negatives in various scenarios._