# tribudata.com

Static site for Tribu (market research powered by a swarm of AI agents), served with GitHub Pages.

- `index.html` — the whole site (hash-routed pages: `#agent-swarm`, `#technology`, `#recruitment`, `#clients`, `#about`, `#free-pilot`, `#privacy`, `#terms`)
- `404.html` — same page, so any path resolves to the site
- `media/` — video clips, poster, subtitles (`Tribu_AgentSwarm.en.vtt`, `.es.vtt`), logo
- `logos/` — client logos (monochrome + dark variants)
- `Tribu_AgentSwarm.mp4` / `.webm` — the full Agent Swarm video (2:07)
- `CNAME` — custom domain (tribudata.com)

Built from the prototype with `build_prod.py` (Claude session, Oct 2026). Pilot forms open a prefilled email to the contact mailbox until the Supabase backend is connected.
