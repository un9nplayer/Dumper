# Dumper

**Dumper** is a Python script that compresses files or directories into a ZIP file, uploads them to [file.io](https://www.file.io/) for easy sharing, and generates a shareable link. Additionally, Dumper sends a notification with the download link to a specified Discord webhook, making it convenient for collaborative workflows or quick file sharing.

## Features

- Compresses directories into a ZIP file automatically.
- Uploads files or directories to file.io.
- Generates a shareable one-time download link.
- Sends a notification to a Discord channel with the download link.

## Support

- Window/Linux both

## Requirements

- Python 3.x
- Install required packages with:
  ```bash
  pip install requests

## Usage
  ### Linux
- Command-Line Arguments
- Argument	Description
  ```bash
  python3 Dumper.py -f /path/to/file
  python3 Dumper.py -d /path/to/directory

### Windows

- You can use it with python or without python
- with python use same as Linux usage
- without python follow:
  ```bash
  pip install pyinstaller
  python3 -m pyinstaller --onefile Dumper.py

- find the `Dumper.exe` file in `dist` folder in same dir. 

## Example

- Uploading a file and receiving a link:
  ```bash
  python3 Dumper.py -f example.txt
- Uploading a Dir and receiving a link:
  ```bash
  python3 Dumper.py -d /path/of/dir

## Configuration

- To use the Discord notification feature, add your Discord webhook URL in the script:
  ```bash
  discord_webhook_url = 'https://discord.com/api/webhooks/YOUR_WEBHOOK_URL'

### Made with 💖
