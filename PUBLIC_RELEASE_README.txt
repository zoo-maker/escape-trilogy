ESCAPE TRILOGY — Ver.1.4 PUBLIC RELEASE

GitHub Pages:
Upload the four HTML files in ESCAPE_TRILOGY_FINAL/ to the repository root.

Security hardening:
- Stage-clear postMessage target restricted to same origin.
- Parent accepts messages only from same origin and the active game iframe.
- Referrer policy set to no-referrer.
- Browser permissions for camera, microphone, geolocation, payment, USB, serial and Bluetooth disabled at page level.
- No external scripts/assets/network endpoints added.
- No gameplay changes were made.

Ver.1.4.1 compatibility fix:
- Local file:// testing now permits the stage-clear bridge only from the active iframe.
- GitHub Pages / HTTPS publication remains strict same-origin.
- No gameplay content changed.

Ver.1.4.2 seamless transition:
- Cave clear no longer shows the old replay/clear card inside the trilogy.
- Office clear keeps its whiteout and transfers directly to Hotel without an intermediate replay/start screen.
- Office and Hotel start automatically when entered from the trilogy launcher.
- Standalone failure/retry behavior is preserved.
- Public-release message security remains in place.

Ver.1.5 FINAL PC + MOBILE
- Absolute baseline: Ver.1.4.2 SEAMLESS TRANSITIONS.
- Added only mobile controls: joystick, touch look, E, RUN, landscape notice.
- Desktop controls, gameplay, maps, monsters, puzzles, endings, transitions and public security unchanged.
