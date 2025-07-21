# Personal-image-finder

This app automatically selects the best matching images from a Google Drive folder for each content block in a Google Sheet.

## Setup on Render

1. Create a new "Web Service"
2. Use this repo as source
3. Set the following environment variables in Render Dashboard:
    - `OPENAI_API_KEY`
    - `SHEET_ID`
    - `DRIVE_FOLDER_ID`
    - Google Service Account details (each key as separate ENV var)
4. Deploy and run
