# Chatter

## What if your Glyph started talking nonsense?

As you type, Chatter brings your Glyph Matrix to life—one character at a time.

Choose from everyday catchphrases, mild to moderate English swears in the Slang collection, or food names from around the world.

Have something of your own to say? **Pinned text** keeps your message on the Glyph Matrix for one hour.

Chatter displays your selected phrases—not what you’re actually typing. The typing feature does not save your input text to a typing history or send it to a server. Messages you explicitly pin are saved locally to keep them displayed.

**You do the typing. Let your Glyph Matrix do the chatter.**

> This repository distributes APK downloads, release notes, and usage documentation. The application source code is not published here.

## Downloads

[**Download Chatter 1.0.2 APK**](https://github.com/p547850824-commits/chatter-downloads/releases/download/v1.0.2/Chatter-1.0.2.apk) · [All releases](https://github.com/p547850824-commits/chatter-downloads/releases)

APKs are provided under **Releases**. Download the `.apk` asset, not GitHub’s automatically generated source archives; those archives contain this repository’s documentation only.

This is an early preview release. Check the release notes before installing.

### Upgrading from a private test build

Public releases use a dedicated signing certificate. If you previously installed a debug/private test build, Android may reject an in-place update. Save any pinned message you want to keep before manually uninstalling the old build and installing this APK; uninstalling removes app settings and saved pins. Then re-enable accessibility access. Future public releases will retain the same signing key.

## Features

- Three phrase collections: Catchphrases, Slang (30 mild to moderate English swears), and Food.
- A paper-cut style portrait with a fixed orientation and live Glyph overlay.
- A live, device-sized Matrix preview with a typing playground.
- Long words move left to keep the newest letter visible.
- One-hour pinned messages, including Chinese text using Fusion Pixel Font.
- One-column scrolling for pinned text.
- Pinned messages take priority over typing effects until cleared or expired.

## Compatibility

Uses the official [Glyph Matrix SDK 2.0](https://github.com/Nothing-Developer-Programme/GlyphMatrix-Developer-Kit). Supported SDK targets are **Phone (3)** (25×25) and **Phone (4a) Pro** (13×13), with Android 14+ and compatible Nothing OS firmware. App-based Matrix control requires system version 20250801 or later, according to the SDK documentation. Phone (4a) Pro was used for device testing; Phone (3) has not been physically tested for this release.

## Getting started

1. Download and install the APK from Releases. Android may ask you to allow installation from your browser or file manager.
2. Open Chatter and follow its accessibility authorization entry to enable the typing service.
3. Choose a phrase collection and turn on the switch.
4. Type in another application to advance the phrase, or use **Try typing here** for an on-screen demonstration. The playground does not send its input to the physical Glyph.
5. Open **Pinned text** to pin a custom message for one hour, or clear an existing message.

If Android restricts accessibility access for a sideloaded app, review its App info → menu → Allow restricted settings option before enabling the service. Availability and wording depend on your Android version.

## Avoid conflicting Glyph effects

Turn off the system Glyph typing effect and other applications writing to the same Matrix when using Chatter. Multiple active effects can interrupt each other.

## Privacy and permissions

The accessibility service detects text-edit activity to advance a preset phrase. It does not display the content you type as that phrase. Pinned text is explicitly supplied by you and saved in app preferences so it can survive an app restart. Clearing a pin removes its saved state; expired pins are no longer displayed. Notification and foreground-service permissions support the pinned-message service.

## Why I made Chatter

The first-party productivity features for the Glyph Matrix are fantastic, while the games that are only fun to try once feel a little too gimmicky to me. Still, they inspired me to explore some more playful uses for the Glyph Matrix.

Quite a few times in everyday life, a pattern lighting up on my Glyph Matrix has caught the attention of people nearby and prompted them to ask about this interesting phone. I really enjoy those moments when I get to introduce Nothing to someone new.

That made me realize that the Glyph Matrix doesn’t necessarily have to serve only its owner. While I’m using the front of my phone, the Glyph Matrix on the back could display **non-private** information or patterns to the people around me.

With that idea in mind, I made this little feature to let others know that I’m typing. But if anyone tries to read the message displayed on the Glyph Matrix carefully, they’ll probably just end up confused, haha.

**Have fun messing with your friends!**

## Feedback

Use this repository’s Issues page. Include the public phone model, Android/Nothing OS version, app release, steps to reproduce, and expected versus actual behavior. Avoid sharing private messages, device serial numbers, confidential device names, or unredacted logs.

## Credits and rights

The Nothing Glyph SDK is used under its [SDK license](https://github.com/Nothing-Developer-Programme/GlyphMatrix-Developer-Kit/blob/main/LICENSE.md). The SDK itself is not redistributed as a standalone download here. This release is provided free of charge.


Chinese pixel glyphs use [Fusion Pixel Font](https://github.com/TakWolf/fusion-pixel-font) by TakWolf, under SIL Open Font License 1.1; original font and upstream notices are included in the app. Other included components remain subject to their respective licenses.

Chatter is distributed as an application binary. Publishing downloads does not grant an open-source license to the application code. Nothing and Glyph are trademarks of their respective owners. This is an independent project and is not an official Nothing product.
