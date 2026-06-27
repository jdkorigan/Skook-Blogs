# Microsoft Vision - The IQ Era

It's hard to understand the value of "Fabric IQ" unless you see the full picture of how Microsoft coordinates its IQ family.

There are 3 IQ in Microsoft family:

- **Fabric IQ** unifies enterprise data (semantic models) by adding **ontology + graph**, enabling real-time + historical understanding for **analytic and operational agents**.
- **Foundry IQ** builds AI **decision agents** using **RAG** to inject trusted knowledge (hospital protocols, medication rules, **robot SOPs**) and produce context-aware, auditable decisions under governance.
- **Work IQ** embeds AI into daily workflows via **Copilot** (meetings, chats, tasks), enabling confirmation, handoff, and execution in the apps people already use.

## Hospital example

I'm currently working on a project and it could be solved with the IQ family (but it is still in preview, so it is not for a prod use case right now).

In the scenario where a nurse requests a **stat** medication (e.g., antibiotic), Copilot captures intent in Teams, Fabric provides unified context, Foundry selects the best robot route/priority under constraints, and Work IQ drives the action back with confirmation and tracking (including ETA updates).

## Diagrams

The article includes a **scenario workflow** diagram and a minimal implementation lens (agent roles).

---

Full article: [Microsoft IQ Era](https://jdkorigan.github.io/SKOOL-Blogs-Publication/02-Skool-Blog-IQ-Strategy/microsoft-vision-iq-era.html)

## Build

Shared toolkit: `0-Skool-Blog-Templates/README-BUILD.md`

```powershell
cd 0-Skool-Blog-Templates && uv sync

# Matplotlib diagrams (article-specific — stay in this module)
uv sync --extra diagrams
uv run python ../2-Skool-Blog-IQ-Strategy/code/build_iq_scenario_workflow.py
uv run python ../2-Skool-Blog-IQ-Strategy/code/build_iq_implementation_architecture.py

# HTML export (thin wrapper → shared scripts in 0-Skool-Blog-Templates)
cd 2-Skool-Blog-IQ-Strategy
python code/export_md_to_html.py

# Infographic from canvas
python code/build_infographic_from_canvas.py
```

## Publish

```powershell
.\0-Skool-Blog-Templates\scripts\publish_to_publication.ps1 -Module 2-Skool-Blog-IQ-Strategy -Slot 02
```
