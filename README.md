# homepath-site

Static marketing + privacy site for **HomePath** (homepath.co.uk), the UK mortgage toolkit app by 1707 Ltd.

No build step — plain HTML/CSS/JS, deployed to **Cloudflare Pages**.

## Structure

- `index.html` — landing page
- `privacy/index.html` — privacy policy (`/privacy/`)
- `llms.txt` — AI/LLM discovery file
- `robots.txt` — crawler rules (allows GPTBot, ClaudeBot, PerplexityBot)

## Local preview

Open `index.html` directly, or serve the folder:

```sh
python3 -m http.server
```

## Deploy

Cloudflare Pages — connect this repo, no build command, output directory `/`.
