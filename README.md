[README.txt](https://github.com/user-attachments/files/35302002/README.txt)
BUDDY BOARD GAME - XBOX BROWSER EDITION

Files
- index.html: the complete game. This is the website's entry page.

Xbox controller layout
- A: select a focused button / roll the dice when playing
- B: close the game menu or How to Play
- D-pad or left stick: move focus between buttons
- Menu (three lines): open/close the in-game menu

The game still supports keyboard, mouse and touch input as well.

PUBLISHING
This package is ready to publish as a static website, but it has not been uploaded to a public host. You need to publish it using an account you control. The game loads Three.js from cdnjs, so the Xbox needs an internet connection.

PUBLISH WITH GITHUB PAGES (free for public repositories)
1. Sign in to GitHub and create a new PUBLIC repository, for example buddy-board-game.
2. Upload index.html from this folder to the top level of that repository.
3. Open the repository's Settings > Pages.
4. Under Build and deployment, choose Deploy from a branch.
5. Choose branch main and folder /(root), then Save.
6. Wait for GitHub Pages to publish. The website address will be shown on the Pages screen.
7. On Xbox, open Microsoft Edge and enter that website address.

GitHub's official instructions:
https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site

CONTROLLER NOTE
The page uses the standard browser Gamepad API. Microsoft documents this API for Edge, but controller input exposure and browser-reserved buttons can vary by device/browser build. Test on the actual Xbox Series X after publishing. The Xbox browser itself also uses some controller buttons for browser navigation, so the in-page mapping is deliberately kept to A, B, D-pad/left stick and Menu. If Edge does not expose the controller to the page, full in-game controller input would need further platform-specific investigation.
