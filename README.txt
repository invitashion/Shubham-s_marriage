SHUBHAVIVAH - Shubham & Monali (Wedding Invitation Website)
=============================================================
Files
  index.html      -> main page (8 book-style pages, page-turn from bottom-right)
  css/s.css       -> styling (minified)
  js/a.js         -> scripts (obfuscated)
  assets/music.mp3 -> background song (plays automatically on first tap)

HOW TO PUT THIS ON GITHUB PAGES (step by step)
  1. Go to https://github.com and log in (create a free account if you don't have one).
  2. Click the "+" (top-right) -> "New repository".
       Repository name : shubham-monali-wedding   (or any name you like)
       Visibility       : Public
       Do NOT tick "Add a README file".
     Click "Create repository".
  3. On the empty repo page, click "uploading an existing file".
  4. Drag in index.html, and ALL THREE folders css, js and assets (drag the folders
     themselves, GitHub keeps the folder structure). Wait for the upload to finish,
     then click "Commit changes".
  5. Go to the repo's Settings tab -> Pages (left sidebar).
       Source        : Deploy from a branch
       Branch        : main   /  (root)
     Click Save.
  6. Wait 1-2 minutes, then refresh that Settings -> Pages screen. Your live link
     appears there, looking like:
       https://<your-username>.github.io/shubham-monali-wedding/
  7. Open that link on your own phone once to check everything (page-turn, music,
     WhatsApp buttons, map), then share it on WhatsApp / SMS with your guests.

Updating it later
  Whenever Claude gives you new files, go to the repo, open each changed file,
  click the pencil (Edit) icon, delete the old content, paste the new content,
  and commit. Or delete the old file and upload the new one the same way as step 4.

Notes
  * iPhone: always share the https://...github.io link, not the raw HTML file.
  * This build is minified/obfuscated - don't try to hand-edit it. Ask Claude to
    change anything and re-export these files.
