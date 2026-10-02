# Jason ProAI FS Checking Tool v7.2 — test report

## Sign-in
- Owner JC signs in; role = owner
- View-only cannot extract, copy prompts, or download Word
- Passwords hashed in this browser after first successful sign-in
- Gate is a courtesy lock — host privately for real security

## Extract
- Sample pack: ACME Pte. Ltd., year ended 31 Dec 2025, FRS / SFRS
- Quality = Strong coverage
- Manual company / period / framework override fields work
- HEIC rejected with convert-to-JPEG/PDF message
- Old .doc rejected with save-as-.docx message
- IndexedDB used for extract restore

## OCR
- Page from–to range and Cancel OCR present
- Warns on >40 pages and packs >25 MB

## Prompts
- Target AI: Grok / Gemini / ChatGPT / Claude
- Long packs: Copy part 1 / 2 / 3 with overlap
- Clipboard fail auto-downloads .txt

## Findings
- Register present: HIGH counted once (no duplicate from [HIGH] lines)
- Findings board lists deduped items

## Product
- No Download HTML / PWA buttons inside the tool or login
- Word via compressed JSZip
- Wipe-on-close optional

## Still HTML-limited
- Not bank-grade login
- Cannot parse old .doc or native HEIC
- Does not call Gemini/GPT itself
- Scan-table OCR will not match Adobe
