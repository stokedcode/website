# stokedcode.com

Company website of Stoked Code sp. z o.o. Plain HTML and CSS, no build step.

- `public/` – the site (published as-is)
- `.github/workflows/pages.yml` – deploys `public/` to GitHub Pages on every push to `main`

## Local preview

```sh
docker compose up
```

Open http://localhost:8080.

## Hosting

GitHub Pages (Settings → Pages → Source: GitHub Actions, Custom domain: `stokedcode.com`, Enforce HTTPS). DNS records at the registrar:

| Type  | Name | Value |
|-------|------|-------|
| A     | @    | 185.199.108.153 |
| A     | @    | 185.199.109.153 |
| A     | @    | 185.199.110.153 |
| A     | @    | 185.199.111.153 |
| CNAME | www  | stokedcode.github.io |
