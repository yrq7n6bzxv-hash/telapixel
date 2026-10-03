# TelaPixel website

Public website, privacy policy and support for TelaPixel, an iPhone and iPad pixel-art app.

This repository contains website files and promotional assets only. It does not contain the Swift app source, signing certificates, credentials, users’ artwork, test results or device logs.

GitHub Pages publishes the `main` branch root. Preview locally with `python3 -m http.server 8080`.

Screenshots and the demonstration are actual app captures using built-in starter artwork. No analytics scripts, external fonts or tracking pixels are included.

## Media refresh

The media below was refreshed on 3 October 2026 from TelaPixel 2.0.0 build 29, source commit `5e1552b97a77a48cb1da287bb7fe094fce5a1afd`, using real dedicated simulator captures. Keep raw captures, test logs and source-hash evidence outside this public website repository. Do not resize an iPhone screenshot to impersonate an iPad or another phone layout.

| Website asset | Required capture |
| --- | --- |
| `assets/editor.png` | English `release-en-02-artwork-editor.png`, native 1320 × 2868 iPhone |
| `assets/starters.png` | English `release-en-01-starter-gallery.png`, same iPhone run |
| `assets/reference-ipad.png` | English `release-en-04-reference-preview.png`, native 2064 × 2752 iPad |
| `assets/demo.mp4` | Fresh English recording of the final interface; inspect the entire video and its poster |

The home page uses the iPad reference preview in place of the obsolete paper-preview screenshot. Retain `assets/app-icon.png` unless the shipping icon changes.

The App Store screenshot sets are separate: English, Italian, French and Spanish, with three reviewed screenshots per language for both native device sizes (editor, gallery and reference preview). The website uses English media. App Store preview video is a different format from screenshot images; use Apple’s current specifications and do not label an English recording as another language.

Before publishing, check local links and image dimensions, review desktop and narrow layouts, and review privacy/support wording against the final app behavior. Stage only website HTML/CSS, this README, `.nojekyll`, and the intended public assets. Never copy the app repository, `.xcresult`, DerivedData, signing material or a simulator container here.
