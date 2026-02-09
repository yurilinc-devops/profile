# Redirect site for Yuri Lincoln

This tiny repository's sole purpose is to redirect visitors to the actual landing page hosted at:

https://yurilinc-devops.github.io/Landing-Page/

How to use

1. Create a new GitHub repository named `yurilinc.github.io` under your GitHub account (this will publish at `https://yurilinc.github.io`).
2. Clone the new repo locally and copy the files from this folder into it, or push this folder as the new repo.

Example commands:

```bash
# from this workspace
cd redirect-site
git init
git remote add origin git@github.com:your-username/yurilinc.github.io.git
git add .
git commit -m "Initial redirect site"
git branch -M main
git push -u origin main
```

Notes
- The `index.html` uses a 0-second meta refresh plus a JS fallback.
- You can optionally add a simple `CNAME` file if you want a custom domain.
