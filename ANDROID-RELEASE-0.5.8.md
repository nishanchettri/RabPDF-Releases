# RabPDF Android 0.5.8

Package: app.rabpdf.android. Version code: 13.

- Grid-only tool navigation; removed the sidebar toggle.
- Redesigned About panel with seven small hand-painted regional icons, including Darjeeling, privacy copy and clickable contact links.
- QR creation and scanning grouped under QR tools.
- Dedicated header language picker with touch-friendly radio choices.
- Nepali added for main controls, tool labels, and capture commands. Untranslated
  diagnostic/help messages fall back to English. Translations need fluent-speaker review.
- CameraX/OpenCV document capture replaces Google's document-scanner UI.
- Auto capture shows a 3-2-1 countdown gated on document corners remaining steady.
- Manual capture, capture preview, next-page/finish/retake choices, and +1 Add page.
- Existing editor, PDF export, purchases, and processing ring retained.

The camera now requires permission. Photos remain local. Google QR-scanner
services and Google Play billing are still present. Permission denial leaves photo
import available. The custom scanner does not include Google's shadow/stain cleanup.

Physical-camera testing is required before promoting to production: check capture
stability, dim/blurred scenes, crop quality, denial/retry, cancellation, backgrounding,
and multi-page/ID/book export. Emulator/synthetic tests cannot prove camera quality.
