# RabPDF Windows 1.5.7

- Added a clear warning before upscaling when the input and chosen method exceed the 12-million-pixel processing limit.
- Explains the AI model's native 3x intermediate, even for 2x output, and suggests Lanczos at 2x when supported.
- Checks every file in a batch before processing begins. No files are converted if a selected image exceeds the limit.
- Keeps the existing safety limit and original images unchanged.

MSIX package version: 1.5.7.0. Store submission and certification are separate from this release.


# RabPDF Android 0.5.11

Version code: 16. Application ID: app.rabpdf.android.

- Added an image-size warning before upscaling begins.
- Explains the AI processing limit and suggests a supported smaller scale or Lanczos method.
- Checks batch images before conversion and keeps original files unchanged.

## Google Play release notes
<en-US>
Added a clear warning before upscaling oversized images. The message explains the processing limit and suggests supported alternatives before conversion starts. Batch images are checked in advance, and your original files remain unchanged.
</en-US>
