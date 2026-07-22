# Portfolio Starter — Deployment & Customization Guide

## 1. Put this on GitHub

1. Create a new repository on GitHub named **exactly** `yourusername.github.io`
   (replace `yourusername` with your actual GitHub username). This special name
   is what makes GitHub Pages serve it at the root URL automatically.
2. Upload all these files to that repository (drag-and-drop on GitHub's web UI
   works fine, or use git from the command line — either way, no build tools needed).
3. Go to the repo's **Settings → Pages**. Under "Source," select the `main`
   branch and `/ (root)` folder, then save.
4. Wait 1–2 minutes. Your site will be live at `https://yourusername.github.io`.

## 2. Customize the content

- **index.html** — replace every placeholder paragraph (marked in plain
  English, not lorem ipsum) with your real bio, resume highlights, and
  section text.
- **resume.pdf** — add your actual resume PDF to the root folder so the
  download button on the Resume section works. (Or delete that link if you'd
  rather keep the resume web-only.)
- **samples/** — each file is one portfolio piece. Duplicate the pattern to
  add more; just update the `<a class="card">` links on the homepage to match.
- **blog/** — same pattern for posts. This is the easiest part to keep adding
  to over time, which is good — a portfolio that visibly grows is itself a
  signal to hiring managers.

## 3. Iterating with Claude

Once you've got real content (a real bio, resume, and one or two writing
samples), come back and paste them in — I can:
- Rewrite the placeholder copy in your voice
- Add a proper contact section or a simple contact form
- Turn the blog into something you can update by just dropping in Markdown
  files instead of hand-writing HTML each time
- Do a design pass once there's real content in place (styling decisions
  land better against real text than placeholder text)

## 4. Custom domain (optional, later)

If you eventually buy a domain, GitHub Pages supports it directly — Settings →
Pages → Custom domain. Not necessary to start; `yourusername.github.io` is a
perfectly credible portfolio URL on its own.
