# Sensei — Privacy Policy

*Effective 2026-09-18.*

Sensei（先生）is a Chrome extension for learning Japanese from video through
in-context word lookup. This policy describes all data handling. The short
version: **Sensei collects no data.**

## What Sensei does with data

- **Nothing leaves your device.** Sensei makes no network requests. The
  dictionaries (JMdict, JMnedict, KANJIDIC2, pitch accent, frequency and
  grammar data) are bundled inside the extension and read locally.
- **Text you look up stays local.** Selected text and captured subtitle lines
  are analyzed on your device and shown in the side panel. Nothing is sent to
  any server.
- **Your vocabulary history is stored locally** in your browser's IndexedDB —
  the words you looked up, the sentences they came from, the video title and
  URL of the page you were on, and your known-word flags. You can delete any
  of it, or all of it, from the History view at any time. Uninstalling the
  extension removes it.
- **Whole-line translation runs on-device** via Chrome's built-in Translator
  API. The text is processed by Chrome on your machine; Sensei sends nothing
  to a translation service. On machines where the on-device model is
  unavailable, the Translate button does not appear — there is no online
  fallback.
- **No images are ever stored.** Sensei does not capture, retain or transmit
  screenshots or video frames.

## What Sensei does not do

- No analytics, telemetry, or crash reporting.
- No ads, no third-party SDKs.
- No accounts, no sign-in, no cookies.
- No sale or sharing of any data — there is no data to sell or share.

## Permissions, in plain language

- **Access to websites (`<all_urls>`)** — so the 学 lookup button can appear
  the moment you highlight Japanese text, on any page. Page content is only
  read when you highlight text or press the capture hotkey, and it is never
  collected, transmitted or stored beyond your local history.
- **Storage / unlimitedStorage** — the bundled dictionaries and your local
  history exceed the default browser quota.
- **Side panel, scripting** — the teaching UI, and re-attaching the lookup
  button in tabs that were already open when the extension updated.

## Changes and contact

If any of the above ever changes, this policy will be updated **before** the
change ships, and the change will be noted in the extension's store listing.

Questions: contact the developer through the Chrome Web Store listing's
support link.
