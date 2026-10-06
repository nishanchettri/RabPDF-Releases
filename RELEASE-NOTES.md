# RabPDF Windows 1.5.6

- Compact rounded action buttons with clean corners and keyboard focus states.
- Stacked mascot and Rab wordmark, with PDF made simple restored.
- Circular processing progress beside the action button.
- Update availability control; installation remains a user choice.
- Sponsored-tool enquiry panel and tier information.
- Refined About panel and Nepali language support.
- PDF compression fixes and existing file-drop and output-location workflows retained.

Portable EXE and FastStart ZIP are unsigned. The unsigned MSIX is prepared for Microsoft Store submission, not ordinary sideload installation. Store certification and publication remain separate steps.


# RabPDF Android 0.5.10

Package: app.rabpdf.android. Version code: 15.

- Refined buttons and clearer processing feedback.
- Updated Rab wordmark and About presentation.
- Compact circular download indicator when a newer release is detected.
- Language selection in the header and Settings, including Nepali.
- Google document scanner restored; scan cancellation keeps existing pages.
- Sponsorship enquiry access stays visible on short tool screens.

PDF and image processing remain on-device. Google services may send diagnostics; purchases use Google Play. No automatic update installation.

Upload the signed AAB to Google Play Console. The APK is for direct installation and testing, not the Play upload. Existing signing identity is retained.


# RabPDF Windows 1.5.4

- Redesigned About panel with seven small, image-only regional stickers, including Darjeeling.
- Clear local-processing privacy copy and clickable support/Instagram links.
- Nepali added for main controls and tool labels; untranslated messages fall back to English.
- Includes the 1.5.3 PDF compression fix: decoding-limit failures preserve original page content and skip the unsupported optimisation step.

Windows is free. Documents process on your computer. Cloud folders may sync exports; external websites have their own policies.

The EXE and FastStart ZIP are portable downloads. The unsigned MSIX is for Microsoft Partner Center upload, not direct installation. Certification is not guaranteed.


# RabPDF Windows 1.5.3

Fixes PDF compression failures caused by decoding safety limits. Content that
cannot be safely decoded is preserved without that optimisation; the completion
message reports skipped optimisation steps. Duplicate-object optimisation runs
on an independent copy to avoid partially modifying the fallback document.

The decompression safety limits remain enabled. Compression can be limited or
produce a larger file when the source is already optimised.

This addresses a reproduced class of failure reported during Microsoft Store
certification. Microsoft's exact test PDF was not provided, and certification
approval is not guaranteed. Android is unchanged.


# Windows 1.5.2 - 2026-10-04

- Compact blue circular processing indicator beside the action button.
- Actual page, file or AI-tile percentages where measurable; loading and final saving use an indeterminate animation.
- Processing indicator is hidden while idle and after completion or failure.
- Click the completed output filename to open it, or use Show in folder to reveal it.
- Existing six-language controls, offline tools and Darjeeling branding retained.

Verification: 26 desktop regression tests, both packaged executable self-tests and a background PDF merge UI test passed. Installed-MSIX workflows remain unverified. This is not Microsoft Store certification.
# Windows 1.5.1 - 2026-10-04

- File drops in PDF input lists with single-file/batch validation.
- QR tools moved into an expandable sidebar section.
- Create QR codes for links, text, Wi-Fi, contacts and email.
- Export QR codes as PNG or SVG with error-correction options.
- Read QR images offline; preview or copy contents before optionally opening
  a confirmed HTTP/HTTPS link. No automatic navigation.
- Language selection for English, German, Italian, French, Spanish and
  Portuguese. Some detailed help/errors/status messages still use English.
- Compact language control and neatly spaced red heart origin line.
- Origin branding: Made with ❤️ in Darjeeling, India 🇮🇳.
- Existing rabbit animation retained.

Verification: desktop regression checks and both packaged self-tests passed.
One UI test lost its window; the affected QR/drop/language checks were rerun
hidden and passed. Physical Explorer drag gestures and installed-MSIX workflows
remain unverified for this release. This is not Microsoft Store certification.

QR codes are static, without analytics or expiry. Wi-Fi QR codes expose their
password to anyone who can scan them. Protect images containing sensitive data.

Only Windows portable binaries are released here. Android, developer keys,
reviewer credentials, build scripts and application source are not published.
