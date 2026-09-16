# binayrawat.github.io

Personal portfolio site for Binay Rawat — Senior Cloud Platform Engineer (AWS, Terraform,
Kubernetes, CI/CD, platform reliability, edge computing).

Plain HTML/CSS/JS, no build step, no dependencies to install. Hosted on GitHub Pages at
[binayrawat.github.io](https://binayrawat.github.io).

## Pages

```
index.html      — home: about, skills, experience timeline, highlights, contact
projects.html   — sanitized project write-ups (problem → approach → result), no company IP
ecs-lab.html    — detailed lab walkthrough: ECS Fargate microservice with Terraform + GitHub Actions
style.css       — shared styling for all pages (dark theme by default, auto light mode)
script.js       — mobile nav toggle, footer year, scroll-reveal animation
```

## Updating the site

Edit the relevant `.html` file (content), `style.css` (design, shared across all pages), or
`script.js` (behavior), then:

```bash
git add -A
git commit -m "Update portfolio"
git push
```

GitHub Pages redeploys automatically within a minute or two of each push.

## Customizing

- Swap the accent color by changing `--accent` / `--accent-strong` in `style.css`.
- Add a new experience entry on the home page by copying a `.tl-item` block in `index.html`.
- Add a new project write-up by copying a `.highlight-card` block in `projects.html`, and
  optionally add a dedicated lab page modeled on `ecs-lab.html` for one with more detail.
