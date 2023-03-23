# MaterialFox

_A Material Design-inspired userChrome.css theme for Firefox_

![Preview](https://user-images.githubusercontent.com/5405629/45172944-21d91900-b24a-11e8-8bc5-03814121b0de.png)

## What this does

Inspired by Google's Material Design and their latest Google Chrome UI, this theme turns your Firefox into a Material-styled web browser. The aim was to style the browser as closely as possible to Google Chrome, where practical.

This is a userChrome.css theme, which means you must manually add it to your Firefox profile. The theme overrides certain browser styles. Currently, only the main UI is affected (settings pages, etc. are not). More elements of the UI may be styled in the future but a broader scope becomes harder to maintain as Mozilla updates their browser code so some UI styles may be culled or redone if they become unmaintainable.

## Installation

1. This theme depends on [uc.css.js](https://github.com/aminomancer/uc.css.js) and [fx-autoconfig](https://github.com/MrOtherGuy/fx-autoconfig) in order to use the `part` selector in author stylesheets. Please follow their installation instructions ([here](https://github.com/MrOtherGuy/fx-autoconfig#setting-up-configjs-from-program-folder)) first.
1. Copy the chrome folder and user.js file into your Firefox profile directory. To find your profile directory, go to about:support or about:profiles.
1. See [Recommended instructions](#recommended-instructions) if you'd prefer a more Chrome-like experience.
1. Restart Firefox.

### Recommended instructions

Add space above tab bar:

- Right click on toolbar -> Customize.
- Check Drag Space checkbox.

Replicate Chrome behaviour for clipped tabs:

- [about:config] Set `browser.tabs.tabClipWidth` to `83` (default is `140`).

Replicate Chrome's "Not Secure" text on HTTP:

- [about:config] Set `security.insecure_connection_text.enabled` to `true`.

## Please note

- Linux is no longer officially supported but you can give it a try – if you'd like to work on it feel free to make a PR.
- Some customization settings may no longer work (such as compact/touch density).
- Some custom themes may clash with the address bar.
- Some themes using transparency might not work.
