# Doom-Wads

Official repository for my custom Doom WAD files and levels.

This repository is where I will keep my Doom mapping projects so I can:

- track revision history over time
- organize and share WAD files with others
- keep project files in one official place

## Repository layout

| Directory | Contents |
|-----------|----------|
| `/maps` | Source/project files organized per map or episode |
| `/wads` | Compiled, playable WAD files ready to load in-game |
| `/releases` | Packaged, versioned WAD releases shared with others |
| `/docs` | Design notes, changelogs, and other documentation |

Each map project can have its own subdirectory under `/maps`, e.g. `maps/episode1-map01/`.

## Notes

- Doom WAD files are stored as binary files in Git (see `.gitattributes`).
- Update `docs/CHANGELOG.md` whenever you finish a new map or release.