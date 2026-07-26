# Panelforge website (GitHub Pages)

Self-contained static site — no build step, no dependencies. Copy **the contents of this
folder** to the root of your public Pages repo, then enable Pages (repo Settings → Pages
→ Deploy from branch → `main`, root).

## Files

| File           | Purpose                                          |
| -------------- | ------------------------------------------------ |
| `index.html`   | Landing page (vendor homepage)                   |
| `docs.html`    | User guide + bridge API reference                |
| `privacy.html` | Privacy policy                                   |
| `support.html` | Support contact + response times                 |
| `style.css`    | Shared stylesheet                                |
| `icon.svg`     | Logo/favicon (same mark as the app manifest)     |

## URLs to paste into Atlassian forms

With Pages at `https://<user>.github.io/<repo>/`:

| Form field                       | URL                 |
| -------------------------------- | ------------------- |
| Partner profile → Homepage URL   | `…/`                |
| Listing → Privacy policy URL     | `…/privacy.html`    |
| Listing → Documentation URL      | `…/docs.html`       |
| Listing → Support URL            | `…/support.html`    |

## Keeping in sync

`privacy.html` and `docs.html` are the rendered versions of
`docs/marketplace/privacy-policy.md` and `docs/user-guide.md` in the main repo — if you
edit one, update the other. If you change the support email, update it in: both HTML
pages, the privacy policy (md + html), and `docs/marketplace/security-answers.md`.
