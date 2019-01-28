# Pitch.AI

* [Dev environment set up](#dev-environment-set-up)
* [Serving the site](#serving-the-site)

## Dev environment set up
Note: this is how Anita had set up her dev env, for the team's reference. She's using a macbook.

* Open command line
* Clone the repo: `git clone https://github.com/pitch-ai/pitch-ai.github.io.git`
* Navigate to the newly cloned folder: `cd pitch.github.io`
* Download [Visual Studio Code](https://code.visualstudio.com), if you don't already have it installed
* Start up Visual Studio Code
* Open the Command Palette, from the toolbar go to `Help` and search `Command Palette`, or if you're using a mac then press `Command + Shift + P`
* Search for something like `code` and select the option that says `Shell Command: Install 'code' command in PATH`
* Go back to command line, and type `code .`
* A new VS Code window should have popped up with the repo folders! :) 

## Serving the site
* Ensure that node.js & npm are both installed. If not, choose your OS and installation method from [this page](https://nodejs.org/en/download/package-manager/) and follow the instructions.
* Next, use your command line to enter your project directory
* To serve the site locally, run `npm run serve` in command line

View other options by typing `npm run`.

