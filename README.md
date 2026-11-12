# Store data

Private store listing data for this game, used by Release Desk (https://github.com/Ecaty/release-desk). Lives as the `Store/` submodule in the game's Unity project.

- `store.json`: shared defaults (name, version, build number, store ids). No secrets.
- `steam/listing.json`, `steam/art/`: Steam store text and images. Release Desk lists the required files and sizes.
- `shots/`: captured screenshots.
- `Logs/latest.txt`: last Release Desk run (not committed).
