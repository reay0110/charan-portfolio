# Charan Reddy Yakkanti: Digital Professional Portfolio

Static site. No build step, no dependencies. Everything in this folder deploys as-is.

```
index.html           the portfolio
styles.css           shared styles
blog/                notes on multiplayer agents and agent swarms
resume.pdf           one page
cv.pdf               two pages
cover-letter.pdf     SpaceX Summer 2027
elevator-pitch.mp4   GPS metadata removed, compressed to 12 MB
```

## Google Docs for review

For each of résumé, CV, cover letter, and blog:

- Paste the content into a new Google Doc
- Share: Anyone with the link, Commenter (or Editor)
- Copy the link

Then search `index.html` for `var DOCS` near the bottom and paste each link between the quotes. Any link you leave empty hides its button.

## Deploy to Vercel

You need Node installed.

```
npm install -g vercel
cd portfolio
vercel
```

Answer the prompts with the defaults. It gives you a preview URL. When you're happy:

```
vercel --prod
```

That's the link you submit.

**Alternative:** push this folder to a GitHub repo, then on vercel.com choose Add New, Project, import the repo, and deploy with no framework preset. Every later `git push` redeploys automatically, which is easier when you're editing.

## Things to know

**SpaceX eligibility.** The posting is restricted under ITAR to U.S. citizens, permanent residents, refugees and asylees. If you aren't one of those, the cover letter needs a different target before you submit.

**Résumé vs CV.** For U.S. industry internships, including SpaceX, send the résumé. The CV is for research and academic applications.

**The original video file** still has GPS coordinates in its metadata. Only share the `elevator-pitch.mp4` from this folder.
