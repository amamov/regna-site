# Regna site

Static Korean product site for Regna, the in-development native iPhone AI agent.
Messaging: practical personal agent, default on-device inference and local storage,
with optional user-key OpenAI/Claude/Google Gemini/Regnax inference. Regna's intended
free/no-subscription core is separate from provider API fees and external processing.
Artwork uses the owner's original PNG, unchanged; see research/POSITIONING.md.
No build dependencies, tracking scripts, forms or third-party fonts.

Preview: `python3 -m http.server 5410 --bind 127.0.0.1`
Deployment: GitHub Pages, main branch, repository root.

Keep launch status honest. Replace the beta-preparation section only after a real
TestFlight public link is verified. Update app privacy details against released code.
App repository: https://github.com/amamov/regna-ios

The latest optional-provider and service features are development work; existing
TestFlight 0.1.0 (2) does not include them. Site disclosures must distinguish local
storage from the content transmitted when a user explicitly selects external AI.
