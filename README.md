# Store data

Private store listing data for this game, used by Release Desk (https://github.com/Ecaty/release-desk). Lives as the `Store/` submodule in the game's Unity project.

- `store.json`: shared defaults (name, version, build number, store ids). No secrets.
- `steam/listing.json`, `steam/art/`: Steam store text and images. Release Desk lists the required files and sizes.
- `play/listing.json`: Google Play short (max 80) and full (max 4000) description.
- `epic/listing.json`: Epic short and full description (same fields as Play; Epic limits not yet in Release Desk rules, verify in the Epic Developer Portal).
- `shots/`: captured screenshots.
- `Logs/latest.txt`: last Release Desk run (not committed).
