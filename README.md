# Bill Splitter

A simple, phone-friendly bill splitter. Enter the bill total, pick a tip percentage (or enter a custom one), set how many people are splitting it, and optionally mark one person as paying double. Shows the tip amount, total with tip, and what each person owes — in large, high-contrast text.

No build step, no dependencies — it's a single static `index.html` file.

## Deploy to Vercel

1. Push this folder to a GitHub repo (see below).
2. Go to [vercel.com/new](https://vercel.com/new) and import the repo.
3. Leave the settings as-is (no framework, no build command needed) and deploy.

Vercel will give you a shareable URL, and every push to `main` redeploys automatically.

## Push to GitHub

From inside this folder:

```
git init
git add .
git commit -m "Bill splitter"
git branch -M main
git remote add origin https://github.com/<your-username>/bill-splitter.git
git push -u origin main
```

Create the empty repo on GitHub first (github.com/new — don't initialize it with a README), then run the commands above with your own username and repo name.
