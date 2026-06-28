# plannotator-inject

Hosted build artifact for **Plannotator inject mode**. Add one tag to any local
HTML document's `<head>`:

```html
<script src="https://ctrlshiftbryan.github.io/plannotator-inject/inject.js"></script>
```

Reload → the Plannotator review chrome mounts → annotate in place → **Preview &
Copy** agent-ready feedback. No server.

A live demo is served at the Pages root (`index.html`).

This repo contains only the built artifact. Source lives in the private
`plannotator` monorepo (`apps/inject`), published via `bun run publish:inject`.
