# Five parts of Riverz AI

These cases describe components of **one product**, each with a different technical problem. They contain implementation summaries and decisions; the application source remains private.

| Component | What it does | Technical focus |
| --- | --- | --- |
| [Video editor](https://github.com/excelenciaempire/riverz-showcase/blob/main/components/video-editor/README.md) | Edits media on a timeline | Reversible audio separation, command identity and preserved edits |
| [Creative generation](https://github.com/excelenciaempire/riverz-showcase/blob/main/components/creative-generation/README.md) | Turns concepts into generated media and an editable plan | Exact editorial timing across provider duration constraints |
| [Research](https://github.com/excelenciaempire/riverz-showcase/blob/main/components/research/README.md) | Collects and reviews product/market evidence | Retained sources, citations, uncertainty and bounded searches |
| [Integrations](https://github.com/excelenciaempire/riverz-showcase/blob/main/components/assistant-integrations/README.md) | Exposes permitted operations to external assistants | Authenticated actors, account permissions and device consent |
| [Windows desktop](https://github.com/excelenciaempire/riverz-showcase/blob/main/components/windows-desktop/README.md) | Edits local projects with optional synchronization | Offline state, independent windows and divergent revisions |

Research supplies product context; generation produces media; the editor assembles it. Integrations provide assistant access, while desktop adds a local runtime.

[Overview](README.md) · [Engineering](ENGINEERING.md)
