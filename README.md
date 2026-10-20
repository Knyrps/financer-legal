# financer-legal

Public pages for the self-hosted financer app (GitHub Pages):

- `privacy.html`, `terms.html` (and both on `index.html`): the privacy notice and terms for the Enable Banking registration.
- `callback.html`: the Enable Banking redirect URL. It forwards the bank's answer (`code` or `error`, and `state`) to the financer callback address that financer encoded in `state`, so a local financer (`http://127.0.0.1:5173`) works behind an https redirect URL.

Source of the texts: `docs/legal.html` in the financer repository.
