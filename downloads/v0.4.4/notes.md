
- Fixes login on the newer TP-Link web interface (Archer AX12 and similar) when the Username box is left blank. The router always signs in to its local "admin" account, so the app now hashes the credential against "admin" instead of the empty box. Before this, the router would accept and decrypt the login and still report the password as incorrect.
