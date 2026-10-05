# Release validation: Windows 1.5.4 / Android 0.5.8

## Passed

- 29 desktop regression tests, including compression-limit content preservation and large-text About scrolling.
- Windows single-file and FastStart packaged self-tests.
- 20 JavaScript tests and 12 Android release unit tests.
- Three app-only Android emulator instrumentation tests: document edges/quality, manual two-page capture and review restoration.
- An independent repeat of the two-page capture test.
- Browser About/grid/QR/language checks at 320, 390 and 768 pixels; seven loaded small icons and working contact targets.
- Android APK signature matches the existing RabPDF upload key; package app.rabpdf.android, code 13, version 0.5.8.
- All packaged 64-bit ELF load segments and APK ZIP alignment pass 16 KB checks.
- Microsoft Store manifest identity retained; x64 version 1.5.4.0, unsigned upload package.

## Unresolved / Not verified

The QA emulator repeatedly displayed a **System UI isn't responding** dialog,
including after restarting it without the release builds running. Its cause was
not diagnosed. The passing instrumentation tests invoke controls directly and
do not prove unobstructed touch interaction while that system dialog is present.
This must not be described as a clean camera visual test or dismissed as harmless.

Physical Android camera quality, auto-capture stability in real lighting, crop
accuracy, permission denial/retry, backgrounding, cancellation and scan export
still require phone testing. The countdown state machine has synthetic unit
coverage, not a real-camera acceptance test. Purchases/restoration need Google
Play testing on an eligible account. This is a closed-testing release.

Installed Microsoft Store execution and Microsoft's original failing PDF were
not tested. The compression regression reproduces the decoding-limit failure
class; it does not establish certification approval.

Nepali covers main controls and scanner labels; untranslated text falls back to
English. Translations require a fluent-speaker review.
