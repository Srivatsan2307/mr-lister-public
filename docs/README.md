# Mr. Lister public / docs pages

Public HTTPS site (GitHub Pages):

- Branded share/import: https://share.silverspectresoftware.com/
- GitHub fallback: https://srivatsan2307.github.io/mr-lister-public/

| Page | URL |
|------|-----|
| Import redirect | https://share.silverspectresoftware.com/i/ |
| Import fallback | https://srivatsan2307.github.io/mr-lister-public/i/ |
| Privacy Policy | https://srivatsan2307.github.io/mr-lister-public/privacy/ |
| Terms of Use | https://srivatsan2307.github.io/mr-lister-public/terms/ |
| Share preview image | https://srivatsan2307.github.io/mr-lister-public/assets/og.png |
| PRO commerce flag | https://srivatsan2307.github.io/mr-lister-public/flags.json |

Custom domain DNS (at the registrar for silverspectresoftware.com):

- Type: `CNAME`
- Name: `share`
- Value: `srivatsan2307.github.io`

Then enable the same custom domain on the GitHub Pages settings for `mr-lister-public`. Old `github.io` import links keep working.

Source repo: https://github.com/Srivatsan2307/mr-lister-public

This `docs/` folder keeps a local copy of those pages for reference. After changing `docs/privacy/`, publish the same HTML to the public repo so the live policy stays in sync.
