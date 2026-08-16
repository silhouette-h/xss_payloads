These files are weaponized XSS payloads rather than just Proof of Concept payloads.
While Proof of Concept payloads do harmless pop-up boxes like 'alert(1)' proves the XSS flaw exists, these weaponized payloads
are malicious javacript code snippets that are written inside a txt file that are designed to do real damage to the victim's browser
like stealing data, hijacks user sessions, logs keystrokes, or forces the victim's browser to execute unauthorized actions.

Here are what each files do:
1. cookiesteal.txt - steals the victim's session cookie.
2. keylogger.txt - logs every keystroke the victim types in his/her desktop.
3. mobilekeylogger.txt - also logs every keystroke when the victim types in a mobile device. but it doesn't log the keys shift, space, caps lock, etc.
4. mobilekeylogger2.txt - same as mobilekeylogger.txt. but it logs every key the victim types in his/her mobile device including the keys shift, space, caps lock, etc.
5. mobilekeylogger3.txt - a complete keylogger script that logs every keystroke the victim types whether the victim is on desktop or a mobile device.
6. listening_server.txt - steps on how to activate a listening server that acts as an attacker-controlled receiver that logs incoming HTTP requests, captures stolen data like session cookies or keystrokes.
