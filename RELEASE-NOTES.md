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
- Existing rabbit animation retained.

Verification: desktop regression checks and both packaged self-tests passed.
One UI test lost its window; the affected QR/drop/language checks were rerun
hidden and passed. Physical Explorer drag gestures and installed-MSIX workflows
remain unverified for this release. This is not Microsoft Store certification.

QR codes are static, without analytics or expiry. Wi-Fi QR codes expose their
password to anyone who can scan them. Protect images containing sensitive data.

Only Windows portable binaries are released here. Android, developer keys,
reviewer credentials, build scripts and application source are not published.
