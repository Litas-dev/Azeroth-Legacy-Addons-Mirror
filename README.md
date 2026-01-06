# Azeroth Legacy Addons Mirror

This repository hosts a mirror of addons for legacy client versions (1.12.1, 2.4.3, 3.3.5).
It is used as the primary data source for the [Azeroth Legacy Launcher](https://github.com/Litas-dev/Azeroth-Legacy-Launcher).

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

## This repository indexes third-party addons.

Where an addon includes a license that permits redistribution, it is mirrored
here under that license and remains the property of its author.

Where an addon license is not clearly stated, only a link to the original
source is provided. No ownership is claimed over any third-party addons.

If you are an author and would like your addon removed or credited differently,
please open an issue and it will be handled immediately.
