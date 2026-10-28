# Mattsby Website

A responsive React + TypeScript + Vite storefront landing page for Mattsby.

## Local development

Install Node.js 20.19+ or 22.12+.

```bash
npm install
npm run dev
```

Open the URL printed by Vite.

## Deploy on Render

1. Create a private GitHub repository named `mattsby-site`.
2. From this directory run:

```bash
git init
git add .
git commit -m "Initial Mattsby website"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/mattsby-site.git
git push -u origin main
```

3. On Render select **New > Static Site**, connect your repository.
4. Build command: `npm install && npm run build`.
5. Publish directory: `dist`.
6. Deploy. The included `render.yaml` also supports a Blueprint setup.
7. After purchasing a domain, add it under the site's **Custom Domains** in Render and follow the DNS instructions Render provides.

## Important before launch

- Product cards are placeholders, not purchasable products.
- `hello@mattsby.com` is a placeholder email address until you buy the domain and set up its mailbox; replace it in `src/main.tsx` before publishing.
- There is no cart, checkout, account system, mailing list, or payment integration yet.
- App-related in-app purchases may require Apple/Google in-app billing depending on the platform and purchase type. Do not substitute Stripe without reviewing applicable store policies.
- Replace placeholder branding and product art with your actual product images and app links when ready.
