# Deployment Checklist

Work through this to actually ship the product.

- [ ] Confirm the hosting/deployment method (e.g., GitHub Pages, Vercel, Netlify) and that it's connected to the right branch.
- [ ] Trigger the deploy and confirm the build step succeeds, not just that it started.
- [ ] Confirm the deploy step succeeds too — a green build does not guarantee a successful deploy.
- [ ] If a deploy fails, check whether it's a real error (bad code/config) or a transient infrastructure error, and re-run before assuming the worst.
- [ ] Visit the live URL yourself (not just the dashboard) and confirm the change is actually visible.
- [ ] Check basic metadata: page title, favicon, and social preview tags render correctly.
- [ ] Record the live URL somewhere obvious (README, operating doc) so it's never a mystery where the product actually lives.
