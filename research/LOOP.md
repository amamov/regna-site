# Website delivery — 2026-10-25

- Published https://amamov.github.io/regna-site/ via GitHub Pages, main/root.
- Confirmed Pages build status `built` and public home/privacy pages load.
- Aside account u0 (ysangsuk78@gmail.com) used for actual DOM and visual review.
- Desktop visual review and 390px iframe mobile viewport reviewed. Main CTA and FAQ
  operated successfully, privacy link opened the intended page.
- Full-page Aside screenshots repeated viewport segments; used viewport capture for
  mobile review. This is a product-site check, not REA parity evidence.
- No TestFlight link yet; development/preparation state is explicit.
- Local preview: http://127.0.0.1:5410, Python server.
- Next: insert verified TestFlight link and update privacy page to match released app.
- No original private research, credentials or analytics included.

## Regna rename verification
- GitHub repository renamed to amamov/regna-site, local folder regna-site.
- Public page at /regna-site/ verified in Aside with Regna Korean/English title,
  branding, navigation, contact link and copyright. Pages status: built.
- Source and filenames scanned: no previous product-name occurrences.
- Repository history is preserved; earlier commits retain their historical names.

## Practical agent positioning / original artwork
- Removed friendship/character-choice sales copy, captions and social metadata.
- Hero, use cases, three value propositions and FAQ now emphasize practical personal
  AI, free/no subscription, on-device inference and locally controlled private data.
- Explicit beta-development status and limits on phone/booking/payment features.
- Original PNG copied unchanged from owner's specified source; hashes match.
- Desktop and 390px mobile viewport visually inspected through Aside; privacy FAQ
  expansion, local links/anchors and absence of retired friendship copy checked.
- Mobile leading sentence shortened after visual review to avoid an orphaned “AI”.
- Local preview restarted after folder rename: http://127.0.0.1:5410.
- Public promotion analysis is bounded to official home, store and company profile;
  complete paid/social marketing coverage and conversion performance remain unknown.
- Public deployment verified: updated HTML and original image hash match served files.
  Existing browser cache initially retained old HTML; versioned stylesheet added so
  the updated layout does not reuse stale CSS. A versioned page URL is used for review.

## Google Calendar / Drive privacy disclosure — 2026-10-25
- Updated privacy.html against the current development app's GoogleAccess,
  GoogleServiceConnectionView, ServiceConnectionsView, GoogleChatQuery,
  ChatController, LocalStore and archive/settings deletion code.
- Disclosed per-service permission requests, primary-calendar event fields,
  Drive metadata/name-prefix search, direct Google query traffic, temporary
  service-screen results versus persisted chat results, local AI context use,
  separate conversation/memory/PDF deletion and device sign-out versus Google
  permission revocation. Kept beta and unverified-live-service status explicit.
- No account data, credentials, tokens, analytics or new scripts were added.
- HTML structure, required data-flow text, absence of active embeds/forms,
  local preview/source byte equality and git diff checks passed. Local URL:
  http://127.0.0.1:5410/privacy.html. Source review is not an original-app REA check.
- Commit b897c09 deployed successfully (Pages status `built`); public privacy URL
  returned HTTP 200 and exactly matched source bytes. Review URL:
  https://amamov.github.io/regna-site/privacy.html?v=b897c09.
- Connector-catalog worker independently opened that public URL in Aside and
  confirmed the Calendar/Drive, storage/deletion and authorization distinctions
  render in the main document. This implementation worker did not control Aside.
  Full app release and Google approval remain separate, pending milestones.

## Optional external AI keys — copy update and deployment

- Updated home title/description context, hero, pricing/value copy, default-mode
  diagram caption, FAQ and a new provider section. Default on-device use remains
  distinct from optional OpenAI/Claude/Google Gemini/Regnax API use and provider fees.
- Updated privacy.html: explicit provider choice, direct transmission of included
  conversation/memory/service-page context, possible inclusion of stored Google
  results, device-only non-synchronizing Keychain, key checks without conversation,
  local deletion versus provider revocation, and already-transmitted data handling.
  Google OAuth and Google Gemini API keys are separate credentials/permissions.
- Checked current RemoteInferenceSession, WebAgent, settings and Keychain source.
  No app files were changed; no real keys, provider accounts or physical device
  were accessed.
- Existing TestFlight 0.1.0 (2) is explicitly distinguished from these development
  features. No claim that all providers have passed live end-to-end validation.
- Reused the existing loopback preview server (explicit --directory regna-site).
  Verified served HTML matches source, internal links/anchors and unique IDs,
  absence of scripts/forms/iframes, and git diff whitespace checks.
- Aside opened http://127.0.0.1:5410/ and reviewed the actual desktop rendering,
  expanded the external-transmission FAQ, and followed its privacy link to
  http://127.0.0.1:5410/privacy.html. Updated sections rendered correctly.
  Aside's Page API did not support setViewportSize, so a new mobile-width visual
  check was not completed in this pass. Screenshots stayed outside Git.
- These are ordinary local site checks, not original-product REA evidence.
  At the initial review no commit/push/deployment had been performed. Root then
  reviewed the diff and authorized deployment within the existing user scope.
- Published content commit `ac140f9a513b8887bc7eb847c092feb72563d585` to main.
  GitHub Pages latest build matched that commit and reported `built` at
  2026-10-25 07:25:04 UTC (16:25:04 KST), with no build error.
- Public home and privacy returned HTTP200 and matched the committed source bytes.
  Aside opened https://amamov.github.io/regna-site/?v=ac140f9 and followed the
  provider-data link to the public privacy page. DOM and a desktop viewport capture
  confirmed the default-mode distinction, provider options, external transfer/API
  fees, development/TestFlight distinction and privacy text. Screenshots stayed
  outside Git. This does not validate the app's live provider calls or Google review.
- Next: keep disclosures synchronized with final app behavior and future release
  status; root is updating the Google verification materials for optional external
  processing. The unfinished mobile-width check remains recorded above.
