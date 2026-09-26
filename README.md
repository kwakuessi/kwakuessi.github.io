# Developer website (all apps)

One free website for all your apps: a home page, one folder per app (with its privacy policy), and one app-ads.txt for AdMob.

```
your-username.github.io/
├── index.html          home page listing all apps
├── app-ads.txt         ONE file for all apps (must stay at the top level)
├── fonts/              shared fonts
└── hold-the-strait/
    ├── index.html      the game's page
    ├── privacy.html    the game's privacy policy
    └── icon.png
```

## 1. Fill in the blanks

- `index.html`: `[YOUR NAME OR STUDIO NAME]` (twice), `[CONTACT EMAIL]` (twice)
- `hold-the-strait/privacy.html`: `[DATE]`, `[YOUR FULL NAME OR STUDIO NAME]`, `[CONTACT EMAIL]` (twice)
- `hold-the-strait/index.html`: `[CONTACT EMAIL]`; later, the store links
- `app-ads.txt`: replace the `google.com, pub-...` line with the exact line from AdMob

## 2. Publish with GitHub Pages (free)

1. On GitHub, create a new repository named exactly `YOUR-GITHUB-USERNAME.github.io` and make it **Public**. Keep your game's code in its own separate private repository.
2. Upload everything in this folder, keeping the folders as they are (drag the whole contents onto the upload page).
3. Settings > Pages: publish from the `main` branch.
4. After a few minutes, check these open in a browser:
   - `https://YOUR-GITHUB-USERNAME.github.io/`
   - `https://YOUR-GITHUB-USERNAME.github.io/hold-the-strait/`
   - `https://YOUR-GITHUB-USERNAME.github.io/hold-the-strait/privacy.html`
   - `https://YOUR-GITHUB-USERNAME.github.io/app-ads.txt`

## 3. Where each address goes

- **Privacy policy URL** (AdMob Privacy & messaging, Google Play, App Store Connect, and the game's `AD_CONFIG.privacyPolicyUrl`):
  `https://YOUR-GITHUB-USERNAME.github.io/hold-the-strait/privacy.html`
- **Developer website** (Google Play: Store listing > Contact details > Website; App Store: Marketing URL):
  `https://YOUR-GITHUB-USERNAME.github.io/hold-the-strait/`
  AdMob always looks for app-ads.txt at the top of the site, so it finds `YOUR-GITHUB-USERNAME.github.io/app-ads.txt` automatically.

## 4. Adding another app later

1. Copy the `hold-the-strait` folder and rename the copy, for example `my-next-app`. Use lowercase letters and dashes only.
2. Replace its `icon.png`, and edit its `index.html` and `privacy.html` for the new app. A privacy policy must describe what that specific app does, so ask Claude to write a new one for each app.
3. In the top `index.html`, copy the `<li>` block for Hold the Strait and change it for the new app.
4. If the new app uses the same AdMob account, `app-ads.txt` needs no change. If it uses another ad network, add that network's line to the same file.
# kwakuessi
# kwakuessi
