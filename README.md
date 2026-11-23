# EPITA

A minimal, public, static course library.

**Website:** https://epita.totob12.com

## Structure

- `public/`: the complete published website.
- Navigation direction: courses → chapters → lessons, current semester first.
- Future lessons can include explanations, examples, exercises and interactive visualizations.

The initial page is a foundation, not a populated course catalogue or final design. No framework or build dependencies are required yet.

## Local preview

Run `python3 -m http.server 8080 --directory public` and open http://localhost:8080. Stop the server with Ctrl+C.

## Deployment

Cloudflare Pages project `epita`, account `a8f49ad6ebe26d6d38841a5e1d49ce6d`.

- GitHub: `TotoB12/EPITA`
- Production branch: `main`; pushes automatically deploy.
- Build command: none.
- Published directory: `public`.
- Preview-branch deployments: disabled.
- Static files only. No backend, database, analytics or runtime secrets.

Revert a commit on `main` to publish an earlier version. Custom domain: `epita.totob12.com`.

## Publication boundary

Everything in this repository is public. Only add original or redistribution-authorized course content. Keep school emails, authenticated Moodle exports, personal information, credentials and private source materials outside this repository.

This is an independent personal project, not an official EPITA service.
