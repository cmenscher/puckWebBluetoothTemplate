This is a template for creating a web app to connect to your Puck.js from a browser. It's only been tested in Chrome Desktop and Chrome for Android.  In my experience, if one of those is connected, the other will not see the Puck until it is completely quit...though multiple tabs can connect to the Puck. If the Puck never gets found, you may have to power cycle the Puck by taking the battery out.  If you know of a way around this, please tell me!

This sample uses the following external libraries:

1. Twitter Bootstrap to make it pretty
2. jQuery 1.12.4
3. The Puck.js Web Bluetooth library

The application incorporates the capacitive sense capability, but you obviously don't have to use it.  I recommend opening the Espruino Web IDE (https://www.espruino.com/ide/) in a separate tab/window to watch the output of the Puck.   Have fun!