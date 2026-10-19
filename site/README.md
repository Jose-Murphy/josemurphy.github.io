# Jose Murphy Portfolio

Static portfolio site for GitHub Pages. It uses plain HTML, CSS, and JavaScript, so there is no build step.

## Run locally

From this folder, start any local web server, for example:

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## Publish on GitHub Pages

1. Create a GitHub repository named `josemurphy.github.io` (or use any repository with Pages enabled).
2. Upload the contents of this folder to the repository root.
3. In **Settings → Pages**, choose **Deploy from a branch**, select `main`, and choose `/ (root)`.
4. If using `josemurphy.com`, add a file named `CNAME` containing only:

```text
josemurphy.com
```

5. At your domain registrar, point the apex domain to GitHub Pages with A records `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, and `185.199.111.153`. Add a CNAME for `www` pointing to `josemurphy.github.io`.

GitHub Pages will issue HTTPS after the DNS records resolve. The current site can stay online until the new Pages site is ready.
