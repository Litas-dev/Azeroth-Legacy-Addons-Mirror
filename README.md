# Azeroth Legacy Addons Mirror

This repository hosts a mirror of addons for legacy client versions (1.12.1, 2.4.3, 3.3.5).
It is used as the primary data source for the [Azeroth Legacy Launcher](https://github.com/YourRepo/Launcher).

## Structure
Each addon has its own folder containing:
- `addon.json`: Metadata (Title, Author, Description, Source Links).
- `README.md`: Human-readable info.
- Zip files: `3.3.5.zip`, `2.4.3.zip`, or `1.12.1.zip`.
- Images: `logo.jpg/png` and screenshots.

## Usage
The launcher consumes the raw `addon.json` files to display and install addons.
Download links point directly to the raw files in this repository.

## Contribution
This mirror is automated. Please do not manually edit files here unless you are fixing a specific metadata issue.
To add new addons, update the upstream list in the launcher's scraper.
