# Contributing to bd-hackathon-archive

First off — thank you. This archive is only as good as the people who feed it, and every problem set you share saves someone else hours of digging through dead links. Whether this is your first-ever pull request or your five-hundredth, you're welcome here.

## Who can contribute?

Anyone. Students, alumni, organizers, judges, participants, or someone who just found an old problem PDF on their laptop. If you have a Bangladesh hackathon problem set, you can contribute it.

## What can you contribute?

- **Problem statement files** — PDFs, images (JPG/PNG), or supporting JSON (e.g. sample test cases) placed inside the correct `problems/` folder
- **New hackathon folders** — if a hackathon isn't listed yet, add it
- **Corrections** — fix wrong or outdated info in the main [README.md](README.md) table

## Step-by-step contribution guide

1. **Fork** this repository.
2. **Navigate** to the correct `hackathons/[hackathon-name]/problems/` folder for the event you're contributing to.
3. **Drop your file(s) in** — PDF, JPG, PNG, or JSON only.
4. **Follow the file naming convention** (see below).
5. **Submit a Pull Request** using the provided PR template.

That's it — no build steps, no dependencies, no CI to fight with. This is a documentation/archive repo.

## File naming rules

Keep names simple, lowercase, and hyphen-separated:

- `problem-a.pdf`
- `problem-b.png`
- `problem-c.jpg`
- `sample-cases.json`

If you know the problem's title, include it:

- `problem-a-matrix-rotation.pdf`

**No spaces, underscores, parentheses, or mixed case in filenames — use lowercase and hyphens instead.**

## Adding a new hackathon that doesn't exist yet

1. Create a new folder: `hackathons/[Hackathon-Name-Year]/problems/`
2. If the folder is empty for now, add a `.gitkeep` file inside `problems/` so Git tracks it.
3. Add a new row to the Hackathon Index table in the main [README.md](README.md).

No per-hackathon README is needed — all hackathon metadata lives in the root README table. The one exception: if a problem set can't be redistributed directly (e.g. it only exists in someone else's private/external GitHub repo), add a short `README.md` inside that hackathon's folder summarizing the problem and linking back to the original source with credit — see [`hackathons/BUET-Hackathon-2026/README.md`](hackathons/BUET-Hackathon-2026/README.md) for an example.

## Share your contribution

Just contributed? Let people know — it helps the archive grow. Feel free to use this on LinkedIn:

> "Just contributed to bd-hackathon-archive — an open archive of Bangladesh hackathon problem sets! 🎉 Check it out: github.com/sakibul-shovon/bd-hackathon-archive #Bangladesh #OpenSource #Hackathon"

## Code of Conduct

Be respectful, be kind, and assume good intent — this project exists for everyone in the Bangladesh tech community, regardless of background or experience level. Harassment, discrimination, or disrespectful behavior of any kind won't be tolerated.
