# minimal-firefox-chrome
A minimal Firefox UI without useless buttons or icons; using keyboard shortcuts allows for more screen space and workspace clarity.

## Installation
1. Download `userChrome.css`
2. Type `about:profiles` in the Firefox address bar to access profile settings.
3. Create a new profile (Optional: you can also use an existing one).
4. Go to the Root Directory of the profile (e.g., `.../.mozilla/firefox/xxxxxxxx.default`).
5. Navigate to the chrome/ folder (if it doesn't exist, create it)
6. Copy the downloaded userChrome.css into that folder
7. Go to `about:config`, search for `toolkit.legacyUserProfileCustomizations.stylesheets`, and set it to true.

## Sorry for the css
Since this is a small project and the Firefox UI is difficult to reverse-engineer, the CSS overrides are based on empirical testing using the Browser Toolbox (Inspector).

Side effects are possible; for now, consider this a "works on my machine" level of maturity. However, the CSS is heavily commented, making it easy for you to tweak and edit the code to suit your specific needs.

## Shorcuts
Since many buttons have been removed, navigation relies on shortcuts. Here are the ones related to the hidden elements:
- Tab : New > `ctrl + t`
- Tab : Close current > `ctrl + w`
- Tab : Nex > `ctrl + tab`
- Tab : previous > `ctrl + shift + tab`
- Search > `ctrl + l`
- page : next > `ctrl + ]`
- page : previous > `ctrl + [`
- history > `ctrl + h`
