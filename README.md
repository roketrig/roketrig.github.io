# roketrig.github.io

Developer site for Buğra Kasarcı's games: https://roketrig.github.io

Each game has its own folder with its icon and privacy policy:

| Game | Privacy policy URL |
|---|---|
| 2048 Olympos | https://roketrig.github.io/2048-olympos/privacy |

## Adding a new game

1. Copy the `2048-olympos` folder and rename it (lowercase, dashes, e.g. `my-new-game`).
2. Replace `icon.png` and edit `privacy.html`: game name, date, and what the game actually collects (ads SDKs, analytics, accounts...).
3. Add a card for the game in `index.html` and a row in the table above.
4. Use `https://roketrig.github.io/<folder>/privacy` as the Privacy Policy URL in Play Console / App Store Connect.

## app-ads.txt

When AdMob gives you an `app-ads.txt` line, put it in a file named `app-ads.txt` at the root of this repo. One file covers all games under the same AdMob account. Use `https://roketrig.github.io` as the "Website" in each store listing.
