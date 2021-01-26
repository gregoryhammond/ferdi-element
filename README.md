# Element for Ferdi / Franz
This is a [Ferdi](https://github.com/getferdi/ferdi) / [Franz](https://github.com/meetfranz/franz) recipe/plugin for [midov.pl Element server](https://element.midov.pl), which is based on [Element](https://element.io/) and [was formerly known as Riot.im and Vector](https://itsfoss.com/riot-to-element/) and is a web client for [matrix](https://matrix.org/).

## Installation
1. Open the Franz Plugins (`dev`elopment) folder on your machine, if the directory does not exist, create it:
  * Mac: `~/Library/Application Support/Ferdi/recipes/dev/`
    * `mkdir ~/Library/Application Support/Ferdi/recipes/dev/`
  * Linux: `~/.config/Ferdi/recipes/dev/`
    * `mkdir ~/.config/Ferdi/recipes/dev/
  * Windows: `%appdata%/Ferdi/recipes/dev/`
    
2. [Download](https://github.com/gregoryhammond/ferdi-riot/blob/master/ferdi-riot.zip) or clone this repo (you don't need the entire repo along with the zip file included, choose one or the other) into the `dev` directory – as sub-directory `ferdi-element` (e.g.).
3. Reload Ferdi.
4. Add New Service.
5. Click on Custom Services.
6. Click on Element (under Community 3rd Party Recipes).
7. Go to the Element service and login.

Huge thanks to [Sylvain Cecchetto for the original recipe / plugin for this](https://github.com/sy6sy2/recipe-riot), [Simon Lüke](https://github.com/semaphor/recipe-element) for the fork that I found on Google.

This has been customized to fit [Ferdi](https://getferdi.com/) and [midov.pl Element server](https://element.midov.pl), but you can modify it to fit your own needs (in package.json).
