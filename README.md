# Riverz AI

**Product research, AI creative generation and video editing for ecommerce teams.**

[Product](https://riverzai.com) · [Product map](CAPABILITIES.md) · [Engineering](ENGINEERING.md) · [Component cases](CASES.md) · [Contact](https://github.com/excelenciaempire/riverz-showcase/issues/new?title=Professional%20inquiry)

Riverz carries product context from research into creative concepts, generated media and an editable video timeline. It also includes Landing Lab, CRO experiments, product-image workflows and marketing/assistant tools. [Explore the full scope](CAPABILITIES.md).

## Product areas

| Area | Focus |
| --- | --- |
| [Product research](https://github.com/excelenciaempire/riverz-research) | Product, audience and market context |
| [Director](https://github.com/excelenciaempire/riverz-director) | Creative concepts, scripts and generation workflows |
| [Video editor](https://github.com/excelenciaempire/riverz-editor) | Timeline, media operations and export |
| [Landing Lab and CRO](CAPABILITIES.md) | Product pages, templates and experiments |
| [Marketing and integrations](https://github.com/excelenciaempire/riverz-integrations-showcase) | Account connections and marketing workflows |

## Inside the application

### Director script workspace

![Director script workspace](assets/director-script.png)

Original web capture, November 3, 2026; native English/dark interface. This is the script workspace with an empty script.

### Landing Lab

![Landing Lab](assets/landing-lab.png)

Original web capture, November 3, 2026; native English/dark interface. This shows the page-creation input and page-type choices.

### Video editor

![Video editor module: generation controls and timeline](assets/editor-workspace.png)

Original web-editor capture, November 3, 2026; native dark interface with an empty project. [Editor engineering case](https://github.com/excelenciaempire/riverz-editor).

[Capture provenance](SCREENSHOTS.md)

## My contribution

I develop the product workflows, web interface, media processing, project persistence and integrations. I also work on a Windows desktop development preview with local editing and optional account synchronization.

The workflow covers product research, concept review, image/video generation, timeline editing and export. The [component cases](CASES.md) explain the different engineering problems within this one product.

## A technical decision

Editing actions use shared planning rules across the interface and programmatic tools. Separating a clip's audio must preserve timing and sound settings, support undo and retain unrelated edits during recovery. [Read the decisions](ENGINEERING.md).

**TypeScript · React · Next.js · PostgreSQL/Supabase · Clerk · Electron · SQLite · FFmpeg**

**All my development work presented here was done with AI assistance.** I use programming and software engineering fundamentals to define requirements, review code, test behavior and take responsibility for technical decisions.

This repository contains documentation and original interface screenshots. Application source is private. The web product requires an account; the Windows version is a development preview.
