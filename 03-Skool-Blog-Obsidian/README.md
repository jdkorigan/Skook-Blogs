# Organize your knowledge in the age of AI.

How to capture YouTube, LinkedIn, and other sources into a local Obsidian vault — and search it with Codex, Claude, or Cursor.

## Public links (SKOOL-Blogs-Publication)

- **HTML:** [organize-knowledge-ai-era.html](https://jdkorigan.github.io/SKOOL-Blogs-Publication/03-Skool-Blog-Obsidian/organize-knowledge-ai-era.html)
- **Hub:** [SKOOL-Blogs-Publication index](https://jdkorigan.github.io/SKOOL-Blogs-Publication/)

After editing Markdown or images, rebuild and copy into `SKOOL-Blogs-Publication/03-Skool-Blog-Obsidian/` then commit the publication repo.

## Build

Shared export lives in **`0-Skool-Blog-Templates`** — see `README-BUILD.md`.

```powershell
cd 0-Skool-Blog-Templates
uv sync

cd ../3-Skool-Blog-Obsidian
python code/export_md_to_html.py --open
```

Optional PDF (`uv sync --extra pdf` in templates first):

```powershell
python code/export_md_to_pdf.py
```

## Publish

```powershell
.\0-Skool-Blog-Templates\scripts\publish_to_publication.ps1 -Module 3-Skool-Blog-Obsidian -Slot 03
cd SKOOL-Blogs-Publication
git add -A && git commit -m "Publish 03-Skool-Blog-Obsidian" && git push
```
