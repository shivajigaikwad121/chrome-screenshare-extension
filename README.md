This is an extension that implements the extension-side of [getscreenmedia](https://github.com/henrikjoreteg/getscreenmedia).

It uses window event messages to communicate between the website javascript and the content script (content.js).
The content script in turn uses channel messaging to talk to the backend script that calls [chooseDesktopMedia](https://developer.chrome.com/extensions/desktopCapture)
and returns the sourceId of the chosen window. This sourceId has to be passed back to getUserMedia.

See also [the tutorial for using inline installation](https://developer.chrome.com/webstore/inline_installation).

Running (for testing and development):


- Clone this repo
- Open the manifest file and add `https://localhost:*/*` to **both** url lists
- Open a chrome tab to `chrome://extensions`
- Check "Developer Mode"
- Click "Load unpacked extension" and pick the extension directory


Extension based on [getScreenMedia](https://github.com/HenrikJoreteg/getScreenMedia)

For instructions about branding and deploying your own copy of this extension, see BRANDING.md
