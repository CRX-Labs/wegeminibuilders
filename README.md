# Gemini Builders Community

**The community website for Gemini Builders Community at United Institute of Technology, Prayagraj.**

[Visit the community page](https://gcb-hub.netlify.app/)

Gemini Builders Community (GBC) is a student-run AI-builder community at United Institute of Technology, Prayagraj, focused on learning by building with Gemini and other AI technologies. The page presents the community's mission and principles, highlights activities and member builds, and gives interested students a way to connect. The site also reflects the community's Google Student Ambassadors program context.

> **Repository notice:** This is a public repository for visibility and documentation of a community-specific website. It is **not** an open-source tool, starter template, SDK, or software package offered for reuse. Public visibility does not grant permission to reuse the source code, design, copy, data, or assets. See [Usage and rights](#usage-and-rights).

## What the website presents

- **Community identity** — an introduction to GBC and its focus on building with AI.
- **Manifesto** — the community's principles, including builders over consumers, learning together, experimenting, and shipping practical work.
- **Events** — completed activities and planned sessions or build sprints.
- **Community builds** — a showcase area for projects made by community members.
- **Learning roadmap** — Learn → Experiment → Build → Share → Lead.
- **Community links and join form** — links to community channels and a form for interested students.

## Design direction

The page uses a bold **brutalist / sketchbook-inspired** visual style, with paper-like backgrounds, strong ink borders, offset shadows, hand-drawn character, and a compact monospace accent. The layout is designed around the identity of this particular student community rather than as a generic website template.

## Implementation overview

The site is built with a lightweight web stack:

- **Frontend:** HTML, CSS, and vanilla JavaScript
- **Backend:** Node.js and Express
- **Content:** JSON files for site configuration, events, and showcased builds
- **Server configuration:** environment variables via `dotenv`

### Repository map

```text
.
├── index.html                 # Main community page
├── assets/
│   ├── css/                   # Visual system, components, sections, responsive styles
│   └── js/main.js             # Loads content and renders the page interactions
├── data/
│   ├── config.json            # Community identity, statistics, links, manifesto, roadmap
│   ├── events.json            # Events shown on the page
│   └── builds.json            # Community-build showcase entries
├── backend/routes/
│   ├── events.js              # Event endpoints
│   ├── builds.js              # Build showcase endpoints
│   └── join.js                # Community join-form endpoint
├── server.js                  # Express server and API route registration
├── package.json               # Project metadata and runtime dependencies
└── .env.example               # Example configuration only; never put real secrets here
```

The JSON files and page copy are specific to GBC. Some entries may be placeholders or draft content and should not be treated as verified community announcements without confirmation from the maintainers.

## Project scope

This repository documents and holds the implementation of the GBC community page. It is maintained for this community's own identity, content, and operations. It is **not offered as a hosted service, public API, reusable component library, or self-service deployment kit**.

## Usage and rights

This repository is public so the community page can be viewed and its development can be documented. **It is not an open-source release.** Unless prior written permission is granted by the rights holder, you may not reuse the source code, visual design, written content, or assets in another project, product, or deployment; modify and republish them; redistribute them; sublicense them; or commercially exploit them.

No general open-source license is granted by this repository. All rights are reserved by the respective rights holder(s). GitHub may provide standard platform features for viewing or forking public repositories; that does not grant a general license to reuse this material in another project or deployment. Please do not submit pull requests or propose reuse as a template unless the maintainers have invited that collaboration.

References to Google and Gemini identify the technologies and community context relevant to this project; their names and marks belong to their respective owners. This community website is not a software product published by Google.

## Maintained by

**Gemini Builders Community (GBC)**  
United Institute of Technology, Prayagraj
