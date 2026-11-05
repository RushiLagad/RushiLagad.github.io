# rushilagad.github.io

Personal academic website of **Rushikesh R. Lagad**, PhD student in Animal Science (Bioinformatics and Genomics), Goswami Lab, Department of Animal Science, University of Arkansas.

Live site: https://rushilagad.github.io/

Built with [Hugo](https://gohugo.io/) and the [HugoBlox](https://hugoblox.com/) Academic CV template, deployed to GitHub Pages by `.github/workflows/deploy.yml` on every push to `main`.

## Where things live

| What | File |
| --- | --- |
| Name, bio, links, education, experience, skills, honors | `data/authors/me.yaml` |
| Homepage (research, news, publications, projects, talks) | `content/_index.md` |
| Experience page (funding, leadership, memberships) | `content/experience.md` |
| Publications | `content/publications/<slug>/index.md` |
| Projects | `content/projects/<slug>/index.md` |
| Navigation menu | `config/_default/menus.yaml` |
| Site name, colors, SEO | `config/_default/params.yaml` |
| CV PDF | `static/uploads/resume.pdf` |
| Profile photo | `assets/media/authors/me.png` |

## Local preview

```bash
pnpm install        # or: npm install
hugo server         # http://localhost:1313
```

Requires Hugo extended 0.161.1 or newer (see `hugoblox.yaml`).
