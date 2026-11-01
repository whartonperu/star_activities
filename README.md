# Stargazer Quest

A phone-friendly learning game about light and the night sky over Peru. Lumi the llama guides children through six levels:

1. **Light Hunt**: find the light sources (the Sun, a torch, a light bulb, a candle).
2. **Torch Explorer**: shine a torch around a dark bedroom and learn that darkness is the absence of light.
3. **Light Check**: true-or-false questions about light and darkness.
4. **Dot-to-Dot Sky**: join the stars to draw Orion, the Southern Cross with its Pointers, Cygnus and Pegasus.
5. **Who Am I?**: constellation riddles and a Star Hunter challenge about finding South.
6. **Star Card**: make a pinhole star card for the Juegos Florales festival and see why the holes shine.

Each level awards up to 3 stars. Progress is saved in the player's own browser.

**Play it:** https://whartonperu.github.io/star_activities/

## Publishing with GitHub Pages

1. In this repository, choose **Add file → Upload files**, drag in `index.html` and `README.md`, then select **Commit changes**.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
4. Set **Branch** to `main` and the folder to `/ (root)`, then select **Save**.
5. Wait one or two minutes. The game will then be live at https://whartonperu.github.io/star_activities/

To update the game later, upload a new `index.html` over the old one. The site refreshes on its own within a few minutes.

## Notes

- The whole game is a single `index.html` file with no build step. The only outside resource is the Google Fonts stylesheet. Without it, the game still works and uses system fonts.
- Sound effects start after the first tap, and players can switch them off with the speaker button.
- In real life, children should ask an adult to help with the needle when making the star card.
