# Bob's Universe

A password-protected prototype for the Robert A.F. Thurman Archive: the *Bob's Buddhism* Pop-up Series (Tibet House US, 2026) as a linked web of people, concepts, texts, places, stories and timestamped moments.

`index.html` contains only an AES-GCM–encrypted payload (PBKDF2-SHA256 key derivation). The content is never present in plaintext in this repository; it decrypts in the browser when the correct password is entered. Source data and the build pipeline live outside this repo.

Prepared by Regina Flores Mir.
