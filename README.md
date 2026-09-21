# Michail Spyridakis — XR portfolio preview

Private design review. No public deployment is configured or authorized.

## Preview
Open `preview.html` directly in a browser. It is self-contained, including all images, Greek/English text and styles. For development, serve this directory with any static web server and open `index.html`.

## GitHub version
`index.html` loads `content.json`. The original public repository remains unchanged. The new design is intended for private review before moving to the public repository. The source contains no API keys, passwords, phone number or raw CV.

## Content editing
`.pages.yml` defines Pages CMS forms for the profile, every category, repeated entries, bilingual text and arbitrary additional label/value fields. The owner still needs to connect Pages CMS to the private repository. No browser-only fake save is offered. Once connected, changes are committed to GitHub. Public website updates require hosting to be configured separately; there is deliberately no deploy workflow in this private preview.

Greek and English fields are independent. Automatic machine translation is not enabled. The standalone preview is a snapshot; regenerate it after editing content or design. The earlier Sites-only database and editor are not the backend of this GitHub version.

## Imagery
Two original AI-generated conceptual illustrations: VR headset/controllers and a circuit-board digital twin. They illustrate research subjects and are not screenshots or photographs of completed projects. Icons are inline SVG interface symbols. All assets are local; no analytics or third-party font requests.

## Sources
Content from the user's existing GitHub portfolio. CMS schema follows https://pagescms.org/docs/configuration/content/fields/ and https://pagescms.org/docs/configuration/content/list/ .
