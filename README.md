# hogenhovestraat28.be

Simple static house listing site.

## Live URLs

- **Production:** https://hogenhovestraat28.be
- **Netlify fallback:** https://hogenhovestraat28.netlify.app

## Deploying updates

Just push to GitHub — Netlify auto-deploys on every push to `main`.

```bash
git add index.html
git commit -m "update content"
git push
```

Live in ~30 seconds.

## Stack

- Plain HTML + CSS — single file: `index.html`
- Hosted on [Netlify](https://app.netlify.com) (free tier)
- Domain registered at TransIP

## Domain setup (already done)

- Domain registered at TransIP, nameservers pointed to Netlify DNS
- SSL certificate is provisioned automatically by Netlify

## Costs

- Domain: ~€9/year (TransIP)
- Hosting: free (Netlify free tier — 100GB bandwidth/month)

## Photos

Drop images into the `images/` folder and reference them in `index.html`.
Current placeholders: `hero.jpg`, `photo1.jpg` – `photo6.jpg`.
