# boppad-web-editor-linux

Web editor for [Keith McMillen Instruments BopPad](https://www.keithmcmillen.com/products/boppad/), hacked up a tiny bit for Linux support.

Official editor lives [here](https://files.keithmcmillen.com/products/boppad/editor/).

Tested in Arch Linux.

Works when using Chromium (tested with 111.0.5563.110).

Doesn't work in Firefox (tested with 111.0.1).  Even when everything is delivered from `file:///`, which should be a secure context, `Navigator.requestMIDIAccess()` is not available.
