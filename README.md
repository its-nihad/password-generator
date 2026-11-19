# KeyVault

KeyVault is a cyberpunk-themed password generator that runs entirely in your browser. It is a single HTML file with no dependencies, no external fonts and no build step.

Click this link to view the project: [https://its-nihad.github.io/password-generator/](https://its-nihad.github.io/password-generator/)

You choose a length from 8 to 64 characters and switch uppercase, lowercase, numbers and symbols on or off. There is also an option to skip lookalike characters such as I, l, 1, O, 0 and o. Every enabled type is guaranteed to appear at least once, and a strength meter shows the estimated entropy in bits. Copy puts the password on your clipboard.

Characters are drawn from the browser's cryptographic random generator using rejection sampling, so there is no modulo bias. Nothing is sent over the network and nothing is saved, not even in local storage. To run it locally, open `index.html` in a browser or serve the folder with any local server.
