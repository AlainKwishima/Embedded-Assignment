# Image Upload Monitor

This Python script monitors a specified folder for new image files, uploads them to a specified URL using `curl`, and then moves the uploaded files to another folder.

## Configuration

The script is configured with the following parameters:

- `WATCH_FOLDER`: The folder to monitor for new images.
- `UPLOADED_FOLDER`: The folder to move uploaded images.
- `UPLOAD_URL`: The URL to which images are uploaded.
- `ATTRIBUTE`: The key attribute for the `curl` command.
- `UPLOAD_INTERVAL`: The time interval (in seconds) to wait before checking for new files.

## Requirements

- Python 3.x
- `curl` command-line tool

## Setup

1. Ensure you have Python 3.x installed on your system.
2. Ensure you have `curl` installed on your system.
3. Clone this repository or download the `upload.py` script.
4. Modify the configuration parameters in `upload.py` as needed.

## Usage

1. Create the `uploaded` folder in the same directory as `upload.py` if it does not already exist.
2. Run the script:

```sh
python upload.py
