# Pack Protection prototypes

Static site, no build step. Pages: / (A/B/C picker), /a, /b, /c.

## Deploy to Vercel

Option 1, GitHub (easiest to update later):
1. Create a new GitHub repo and upload the contents of this folder.
2. In Vercel, click Add New > Project, import the repo.
3. Framework Preset: Other. Leave build and output settings empty. Click Deploy.

Option 2, command line:
1. Install Node.js, then run: npm i -g vercel
2. In this folder run: vercel --prod
3. Accept the defaults when asked.

Your links will look like:
https://your-project.vercel.app/a/
https://your-project.vercel.app/b/
https://your-project.vercel.app/c/
