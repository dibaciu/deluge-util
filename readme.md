# Deluge Pushover Notification Script

This repository contains a Python script to send push notifications via [Pushover](https://pushover.net/) when a torrent is added or completed in [Deluge](https://deluge-torrent.org/).

## Features

- Sends a notification to your Pushover device with the torrent name and save path.

## Requirements

- Python 3.x
- Internet connection
- Pushover account and API token

## Usage

Run the script with the following arguments:

`python deluge_pushover.py <torrent_id> <torrent_name> <save_path>`

Example:

`python deluge_pushover.py 12345 "Ubuntu ISO" "/downloads/ubuntu"`

## Configuration

Edit the `user_key` and `deluge_pushover_token` variables in `deluge_pushover.py` with your own Pushover credentials.

## License

MIT License
