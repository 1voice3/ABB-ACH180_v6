ACH180 Trainer — flat GitHub Pages upload

Upload every file in this folder to the ROOT of your GitHub Pages repository. Keep all files together in the same directory. This package contains no subfolders and uses only .html and .txt files.

Files to upload (all are required):
  index.html                              trainer home page
  manual.html                             ACH180 manual viewer
  ACH180-firmware-manual-base64.txt       embedded ACH180 PDF data
  pdfjs-library.txt                       PDF.js library source
  pdfjs-worker.txt                        PDF.js worker source
  PDFJS-LICENSE.txt                       PDF.js license
  README.txt                              these upload instructions

index.txt and manual.txt are plain-text copies for reference only; they are NOT required by the website. The HTML pages are the files that GitHub Pages serves.

Do not rename files. The ACH180 viewer reads the three TXT runtime payloads by name from the same root directory. The viewer needs to be opened through GitHub Pages (or another HTTP/HTTPS web server); browser security restrictions may prevent loading TXT payloads directly from a file:// URL.

The ACH180 firmware manual (3AXD50000955893 Rev B, 522 pages) is included as base64 text, allowing the upload to stay limited to .html and .txt files. The app retains its trainer features and the ACH180 PDF page viewer/highlighting.

The Carrier VFD-13SI manual PDF was not present in the supplied ZIP. Its links are retained in the trainer but cannot show pages until you obtain and separately incorporate that manual. No substitute PDF was supplied or included.

For licensing, retain PDFJS-LICENSE.txt when redistributing this package.
