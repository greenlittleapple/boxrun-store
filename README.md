# BoxRun store

A static page for BoxRun, a custom Deadlock map. The map's menu opens this page in the game's built-in browser to keep
your routes and best times between game sessions.

- The data stays on your PC, in the in-game browser's local storage for this page.
- Requests travel in the URL's `#fragment`, which browsers never send to a server, so nothing is uploaded.
- The page answers through its title, which the game reads.

`store.html` is the whole thing: no other scripts, no tracking.
