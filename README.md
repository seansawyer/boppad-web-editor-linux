# boppad-web-editor-linux

Web editor for [Keith McMillen Instruments BopPad](https://www.keithmcmillen.com/products/boppad/), hacked up a tiny bit for Linux support.

Official editor lives [here](https://files.keithmcmillen.com/products/boppad/editor/).

Just clone/download the project and open `editor.html` directly from disk in your browser.

Tested in Arch Linux.

Works using Chromium (tested with 111.0.5563.110).

Doesn't work in Firefox (tested with 111.0.1) when loaded via `file://`.  Even though this should be a secure context, `Navigator.requestMIDIAccess()` is not available.  A workaround for Firefox is to serve the editor locally.  An easy way to do this if you have Python 3 installed is to run the following from inside the project directory:

```
python -m http.server
```

Then visit http://localhost:8000/editor.html in Firefox to use the editor.
