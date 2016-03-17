# mosaic_map
Project to display a tile of everyone's mapbox styled map like a mosaic using mapbox GL as a start.

1. Design a map with Mapbox Studio.
2. Publish your map and copy the style link.
3. Edit the CSV file `maptimela_styles.csv` and add your name and link to your style.

For just testing the map you just styled.

1. Fork this repo to your github account.
2. Edit the `index.html` file with your public token key provided by mapbox and your style. (This can be edited in the browser, if you are unfamiliar with the git console or git desktop.)
3. If you want a popup, make sure the layer you want to display information is named in the code calling for a popup.
4. Commit your changes.
5. In order for your map to be viewed through your account you must push your changes to your `gh-pages` branch, this is the branch that displays your map. If you are unfamiliar with the "PUSH" process you can delete your gh-pages branch and create a new branch with the same name. To view your map you must type, [your github account name].github.io/mosaic_map/ in the address bar.
