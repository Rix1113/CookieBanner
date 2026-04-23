# CookieBanner
Privacy Policy for cookie-consent-automation-extension

# Privacy Policy

Last updated: 2026-04-23

Cookie Consent Automation Extension is a browser extension that detects cookie consent banners, applies a privacy-first browsing preference, blocks a starter set of known tracker requests, and optionally suppresses cookie banner UI after protection is active.

## Single Purpose

The extension's single purpose is to reduce cookie banner friction and tracking activity while browsing.

## Data Processed Locally

To provide its features, the extension may process the following data in the user's browser:

- The current page domain and URL, used to apply allowlist, blocklist, and per-tab protection state.
- Page content signals related to cookie banners, consent dialogs, buttons, and known consent-management platforms.
- Consent state signals from page-accessible storage, such as known consent keys in local storage or session storage.
- Tracker request signals used to report whether likely tracker activity was observed.
- Extension settings, including default consent preference, emergency stop state, allowlist, and blocklist.
- A short local audit log of recent extension actions.

## Storage

Settings are stored with `chrome.storage.sync` so Chrome may sync them between browsers where the user has sync enabled.

Per-tab status and the audit log are stored with `chrome.storage.local` on the user's device.

## Data Sharing

The extension does not sell user data.

The extension does not send browsing history, page content, consent state, audit logs, or settings to the developer's server.

If the user clicks the donation link, the browser opens PayPal in a new tab. PayPal's own privacy policy applies to that external site.

## Remote Code

The extension does not load or execute remotely hosted code. Extension scripts are packaged with the extension.

## Permissions

The extension requests browser permissions needed to read and update settings, inspect page status, communicate with content scripts, and apply declarative network request rules for tracker blocking.

## User Controls

Users can disable intervention with the emergency stop, turn tracker blocking or banner suppression on or off, and manage allowlisted or blocklisted domains from the popup and options page.
