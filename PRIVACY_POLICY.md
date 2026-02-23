# Tag Otter Privacy Policy

Last updated: February 22, 2026

## What Tag Otter stores

Tag Otter saves the following data to your browser's local storage using the Chrome Storage API:

- **Settings** — your validation preferences (required parameters, approved mediums, enforcement rules, validation profiles)
- **UTM value history** — a frequency count of utm_source, utm_medium, and utm_campaign values you've used, so the extension can flag inconsistencies
- **Dismissed issues** — fingerprints of issues you've chosen to dismiss, scoped by ad account
- **Presets** — saved URL templates you've created in the builder
- **Manual field anchors** — CSS selectors for fields you've manually picked on sites outside the six supported ad platforms

All of this stays on your device. None of it is sent anywhere.

## Network requests

Tag Otter makes one type of network request: an optional health check that sends a request to your destination URL to verify it loads (HEAD first, falling back to GET if the server doesn't accept HEAD). This is off by default. You turn it on in settings, and you can turn it off anytime.

When the health check runs, the request goes directly from your browser to the destination URL. Tag Otter does not proxy, log, or relay the request through any other server.

No other network requests are made. There is no analytics, no telemetry, no usage tracking, and no phone-home behavior.

## What Tag Otter does not collect

- No personal information (name, email, location)
- No browsing history beyond the UTM values described above
- No cookies, session data, or authentication tokens
- No data from pages beyond what's needed to find and validate URL input fields (on supported ad platforms automatically, or on other sites when you manually pick a field)

## Third parties

Tag Otter does not share data with third parties. There are no third-party scripts, SDKs, or services embedded in the extension.

## Data retention

All stored data remains on your device until you clear it. You can clear your UTM history and reset your settings from the extension's options page. Uninstalling the extension removes all stored data.

## Changes to this policy

If this policy changes, the updated version will be posted here with a new date.

## Contact

Questions about this policy can be filed at https://github.com/Justbeian/tag-otter/issues.
