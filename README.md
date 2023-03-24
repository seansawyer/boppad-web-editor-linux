# boppad-web-editor-linux

BopPad web editor hacked up a tiny bit for Linux support.

Tested in Arch Linux.

Works when using Chromium (tested with 111.0.5563.110).

Doesn't work in Firefox (tested with 111.0.1).  Even when everything is delivered from `file:///`, which should be a secure context, `Navigator.requestMIDIAccess()` is not available.
