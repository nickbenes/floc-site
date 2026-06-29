# Front Lines of Code — Site

Marketing/portfolio site for Front Lines of Code (Nick Benes). Single static `index.html`, no
build step, no backend — deployed to Vercel as a static site.

## Status

First draft, pending review (Brand Manager / H5 and Course Product Owner / H7 personas — see
`agents/h5-plans/manifest.md` and `agents/h7-education/manifest.md` in the ObsidianVault) before
the first Vercel deploy.

## Local preview

```
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## Deploy

Connected to Vercel — pushes to `main` deploy to production; PRs get preview deployments
automatically once the repo is linked in the Vercel dashboard.

## Related

- [floc-apps](https://github.com/nickbenes/floc-apps) — the actual tools (todos, food,
  finance). Separate repo, separate Vercel project, linked from this site rather than bundled
  with it — different review cadence (brand/content vs. code) and different audiences.
- [home-apps#115](https://github.com/nickbenes/home-apps/issues/115) — floc-apps architecture
  decision.
