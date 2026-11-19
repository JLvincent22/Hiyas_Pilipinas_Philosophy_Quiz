# Hiyas Pilipinas – Philosophy Quiz

A static, responsive quiz website built from the supplied Philosophy Information PDF.

## Run locally
Open `index.html` in a modern browser.

## Deploy to Vercel
1. Create a GitHub repository.
2. Upload `index.html` (and this README).
3. Import the repository into Vercel.
4. Use the default project settings. No build command is needed; the site is static.

## Use in MIT App Inventor
1. Deploy the site and copy its HTTPS URL.
2. Set the WebViewer's `HomeUrl` to that URL.
3. Enable JavaScript in the WebViewer if the option is available.
4. Tap once inside the page to initialize browser audio. Sound is generated with the Web Audio API after user interaction (no external audio files or network required).

Note: Audio support depends on the Android System WebView version and device audio settings. If a WebViewer build blocks Web Audio, update Android System WebView/Chrome and test the deployed URL in the device browser.

## Included
- All 18 regions and their Hiyas, philosophical themes, situations, choices, perspectives, and reflection questions.
- Choice-based feedback using the wording pattern provided in the PDF.
- Navigation, progress, region jump selector, responsive layout.
- Tap and feedback tones using Web Audio API.

- End-of-journey player summary based on the philosophical perspectives selected (not a personality score or right/wrong grade).
- Final reflection and quiz feedback text areas with automatic saving and a Save My Answers button.
- Written responses are stored in the browser's localStorage on the same device/browser. They are not uploaded to a server and will not automatically sync across devices or browsers. Clearing browser/app data may erase them.
