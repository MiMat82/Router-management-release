
- Fixes logging in to newer TP-Link firmware (such as the Archer AX12) that answered "HTTP 403". The app now sends the login request the way the router's own page does, follows a redirect to https, and tries the other known formats.
- If a router still refuses the login, the error lists what it answered at each step, with a Copy error details button.
- The login screen asks for the router's local password, and explains that it isn't your TP-Link ID.
- New Install OpenWrt page (under Router): checks your exact model and hardware version against OpenWrt's official list, downloads the official image and verifies its checksum, saves a settings snapshot, then installs through the router's own upgrade function. Includes a recovery guide. Routers OpenWrt doesn't support are refused.
