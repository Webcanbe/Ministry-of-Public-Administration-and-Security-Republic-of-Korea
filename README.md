# Ministry-of-Public-Administration-and-Security-Republic-of-Korea

`index.html` — a single-file demo control panel for Korea's disaster-alert text messages (안전안내문자/긴급재난문자/위급재난문자) and civil-defense siren levels (경계경보/공습경보/화생방경보/핵경보/경보해제).

- Not connected to any real broadcast network or physical siren — sending an alert here only updates this page.
- Scanning the QR code (연동 탭) opens a phone-frame view of the same page. When it's opened as a Claude Artifact, sending an alert from the control panel pushes live to any open phone view via the artifact's live-sync capability.
- Opened as a plain static file (e.g. GitHub Pages), the page still works, but the live push between screens needs the Claude Artifact runtime — a static host has no realtime channel of its own.
