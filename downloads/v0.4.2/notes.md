
- Login on newer TP-Link firmware: when the router answers the encrypted login with an empty "HTTP 403", the app now tries the other known login forms in turn (different credential hash, password padding, length counting, without the Origin header), each with a fresh handshake. The form that works is remembered for the session.
- Requests after login are signed the way the router's own web page signs them.
- The error lists every form that was tried.
