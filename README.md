# kshitij-portfolio-data

Structured personal/portfolio data for [Kshitij Khowal](https://github.com/kshitijkhowal), organized by section.

Consumed as a git submodule by [my-portfolio](https://github.com/kshitijkhowal/my-portfolio).

## Layout

| Folder | Contents |
|--------|----------|
| `Socials/` | Name, contact, links, headline |
| `Education/` | Degrees & schools |
| `Experience/` | Jobs & bullet points |
| `Projects/` | Personal / published projects |
| `Skills/` | Raw skill inventories |
| `Achievements/` | Academic & competitive coding |
| `Site/` | Portfolio-only copy (hero, about, nav, skills UI) |

## Conventions

- Dates: `YYYY-MM` or `present`
- Bullet IDs: prefix by domain (`exp-`, `proj-`, …)
- Tags: lowercase kebab-case

## Updating

Edit JSON here, commit & push, then in the portfolio repo:

```bash
cd data && git pull origin main && cd ..
git add data && git commit -m "chore: bump portfolio data"
```
