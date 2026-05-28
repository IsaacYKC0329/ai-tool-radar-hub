# AI Tool Radar Hub

A bilingual, static AI tools directory for global users.

## Deploy on GitHub Pages

1. Create a new GitHub repository.
2. Upload `index.html`, `assets/`, and `README.md`.
3. In GitHub, open `Settings -> Pages`.
4. Set the source to `Deploy from a branch`.
5. Choose the `main` branch and `/root` folder.
6. Save, then wait for GitHub Pages to publish the site.

## Custom Domain

Recommended domain: `aitoolradarhub.com`

After buying the domain, add it in `Settings -> Pages -> Custom domain`.

For an apex domain, add these A records at your DNS provider:

```text
185.199.108.153
185.199.109.153
185.199.110.153
185.199.111.153
```

For `www`, add a CNAME record:

```text
www -> <your-github-username>.github.io
```
