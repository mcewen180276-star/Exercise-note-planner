CLASS PLAN ORGANISER V1

INSTALL ON GITHUB PAGES
1. Unzip this archive.
2. Upload the CONTENTS of the class-plan-organiser folder (index.html, app.js, sw.js, icon.svg, manifest.webmanifest) to the ROOT of a GitHub repository.
3. In Settings > Pages, deploy from the main branch root. Wait for the published link.
4. Open the HTTPS link on Android Chrome or Windows Chrome/Edge and choose Install app / Add to Home screen.

FEATURES
- Import individual files or folders; drag and drop on desktop.
- Auto-categorise based on filename; manually edit category, notes, tags.
- Search filename, notes and extractable text.
- SHA-256 exact duplicate detection, filename-normalisation and text-overlap suggestions.
- Compare extracted text and open original documents.
- Remove into a reversible recycle bin; permanent delete requires confirmation.
- Complete ZIP backup and restore with originals included.
- Offline PWA after first load. All records remain on the local device.

IMPORTANT
- This app does NOT delete source files from your phone/computer. It deletes only its own copies.
- For old .doc/.xls, and scanned PDFs, content comparison may be unavailable. SHA-256 works for all files.
- PDF extraction is basic, and may miss text or produce scrambled text in some PDFs.
- File storage is browser IndexedDB; exporting backups is strongly recommended.
- Importing large collections can consume substantial browser storage.
- Android browser support for importing whole folders varies.
- Text comparison is a suggestion, not proof of duplication. Inspect originals before removing.
- ZIP backup is unencrypted.
