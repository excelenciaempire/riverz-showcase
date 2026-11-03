# Riverz

**AI creative workflows for ecommerce teams.**

[Product](https://riverzai.com) · [Five engineering cases](CASES.md) · [Engineering notes](ENGINEERING.md) · [Juan Rios](https://github.com/excelenciaempire)

Riverz connects product research, creative generation, and video editing. The goal is to carry useful product context through the creative process instead of rebuilding it for each tool.

![Riverz research workflow on a mobile viewport](assets/research-workflow.png)

*Research workflow screenshot, captured October 2026. This is a product interface example, not a performance or customer-results claim.*

## Explore five parts of Riverz AI

[Video editor](https://github.com/excelenciaempire/riverz-editor) · [Creative generation](https://github.com/excelenciaempire/riverz-director) · [Research](https://github.com/excelenciaempire/riverz-research) · [Integrations](https://github.com/excelenciaempire/riverz-integrations-showcase) · [Windows desktop](https://github.com/excelenciaempire/riverz-desktop-showcase)

These are components of the same product. Each public case explains a specific engineering problem and includes a new, isolated Python example using fictional data. [Compare the cases](CASES.md).

## The workflow

1. Gather and organize product context and supporting evidence.
2. Develop creative concepts and generate image or video assets.
3. Assemble and refine media in a timeline editor.
4. Review the work and export through the relevant processing workflow.

## How I build with AI

**All of my development work presented here was done with AI assistance.** I use AI throughout implementation, debugging and validation. I understand programming and software engineering fundamentals, and use them to define requirements, guide the tools, review changes and check how the software actually behaves. I take responsibility for technical decisions and results.

## My work

I develop Riverz across product behavior, the web application, integrations, media workflows, and a Windows desktop development preview.

Representative areas include shared editing behavior across web and desktop, reversible media edits, persistent project state, background processing, and account-scoped MCP access.

## Technical scope

- **Web:** TypeScript, React, Next.js, and Tailwind CSS.
- **Data and accounts:** PostgreSQL/Supabase and Clerk.
- **Media:** FFmpeg/ffprobe, asset libraries, timeline editing, and background workers.
- **Desktop:** Electron with local project persistence; the desktop preview has its own delivery and validation requirements.
- **Integrations:** account-scoped MCP tools and external media services.

## Engineering focus

An editing action needs consistent meaning across interfaces. Separating a clip's audio, for example, must preserve timing and sound settings while allowing a deliberate undo. Saving or recovering an interrupted operation must preserve the user's other edits.

The [engineering notes](ENGINEERING.md) describe these constraints and the validation approach.

## Repository scope

This repository contains a public product and engineering case study. The application source, operational configuration, and customer data are private. The product link may require an account; the desktop preview is not presented here as a generally available signed release.

For professional inquiries, [open an issue](https://github.com/excelenciaempire/riverz-showcase/issues/new?title=Professional%20inquiry).
