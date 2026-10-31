
- Updating no longer stops with "Failed to kill Router Manager". The app now closes completely, including the tray icon, before the installer runs, and reopens afterwards.
- Starting the app while it is already running (for example in the tray) now opens the existing window instead of a second copy.
- Login on newer firmware: the app opens the router's start page first like a browser, and tries the signing step in both request styles. When the router still refuses, the error lists every login step and what the router answered, so it can be fixed for that model.
- Clearer password hint on the login screen.
