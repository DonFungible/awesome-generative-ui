# Awesome Generative UI [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

This repo is a list of resources for building with and learning about generative UI. I curated it based on my experience building generative UI as a full-stack developer. I actively maintain this repository and keep its links up to date.

Generative UI is a new AI interaction modality in which models generate structured user interfaces rather than text alone. By producing dynamic, interactive UI components, AI systems can present information in a format that is more intuitive, actionable, and context-aware. For example, instead of responding with a text list of nearby restaurants, a model could render a restaurant discovery interface complete with images, map integration, ratings, and reservation widgets, enabling users to explore and act directly within the generated experience.

There are three distinct flavors of generative UI:
1. Controlled/Static: select UI from a catalog of pre-built components
2. Declarative: generate the layout or schema, made up of pre-built components
3. Open-ended: generates unique and dynamic UI on-the-fly
<img width="1614" height="974" alt="HI0u2OsbMAAPV5V" src="https://github.com/user-attachments/assets/092a40a3-284d-43f6-80bc-ce4ff740134e" />
<p align="center">
  <em>
    Three flavors of generative UI. Image taken from
    <a href="https://x.com/Saboo_Shubham_/status/2062220865643982875">Shubham Saboo (@Saboo_Shubham_)</a>.
  </em>

</p>
## Contents

- [Implementation](#implementation)
  - [Specifications & Protocols](#specifications--protocols)
  - [Tools](#tools-sorted-alphabetically)
  - [Skills](#skills)
- [Learning](#learning)
  - [Papers](#papers-sorted-by-most-recent)
  - [Videos](#videos-sorted-by-most-recent)
  - [Articles & Posts](articles--posts-sorted-by-most-recent)
- [Apps](#apps)
 
## Implementation
### Specifications & Protocols

- [A2UI](https://github.com/google/A2UI) - An open-source project that includes a format optimized for representing updatable, agent-generated UIs and an initial set of renderers, allowing agents to generate or populate rich user interfaces.
- [AGUI](https://github.com/ag-ui-protocol/ag-ui) - AG-UI is an open, lightweight, event-based protocol that standardizes how AI agents connect to user-facing applications.
- [MCP Apps](https://modelcontextprotocol.io/extensions/apps/overview) - MCP Apps is a standard for letting an MCP server return an interactive UI alongside a tool result.

### Tools (sorted alphabetically) 

- [AI SDK](https://github.com/vercel/ai) - A TypeScript toolkit for building AI-powered applications. Developed by Vercel.
- [assistant-ui](https://github.com/assistant-ui/assistant-ui) - TypeScript and React primitives for building AI chat interfaces with generative UI.
- [CopilotKit](http://copilotkit.ai/) - An SDK for building agents and generative UIs. Developed by the creators of AG-UI.
- [json-render](https://github.com/vercel-labs/json-render) - A generative UI framework that enables UIs to be described as structured JSON rather than frontend code. Developed by Vercel.
- [MCP-UI](https://github.com/MCP-UI-Org/mcp-ui) - An SDK that implements the MCP Apps standard for UI over MCP.
- [Tambo](https://github.com/tambo-ai/tambo) - A generative UI SDK for React.
- [Thesys](https://www.thesys.dev/) - A generative UI API for AI-native applications.
- [Vendo](https://github.com/runvendo/vendo) - An SDK to enable user-driven customization of webapps.

### Skills
- [Pick UI](https://github.com/emilkowalski/skills/blob/main/skills/pick-ui-library/SKILL.md) - A skill for deciding which UI library to use. Developed by [Emil Kowalski](https://x.com/emilkowalski).
- - 

## Learning
### Papers (sorted by most recent)
- [The Missing Layer: Why EdTech Needs Design-Time Generative UI, Not Just Runtime Personalization, Neshaei et al.](https://arxiv.org/pdf/2606.15902) (Jun 14 2026)
- [Rethinking the UI of GenUI: A Tale of Two Designs, Chen et al.](https://arxiv.org/pdf/2606.13843) (Jun 11 2026)
- [Macaron-A2UI: A Model for Generative UI in Personal Agents, Kong et al.](https://arxiv.org/pdf/2605.24830) (May 24 2026)
- [Efficient Personalization of Generative User Interfaces, Peng at al.](https://arxiv.org/pdf/2604.09876) (Apr 10 2026)
- [Generative UI: LLMs are Effective UI Generators, Leviathan et al.](https://arxiv.org/pdf/2604.09577) (Feb 24 2026)
- [The Keyhole Effect: Why Chat Interfaces Fail at Data Analysis, Mohan Reddy](https://arxiv.org/pdf/2602.00947) (Feb 1 2026)
- [Gradual Generation of User Interfaces as a Design Method for Malleable Software, Min et al.](https://arxiv.org/pdf/2601.17975) (Jan 25 2026)
- [Meridian: A Design Framework for Malleable Overview-Detail Interfaces, Min and Xia](https://dl.acm.org/doi/epdf/10.1145/3746059.3747654) (Sep 27 2025)
- [Towards a Working Definition of Designing Generative User Interfaces](https://arxiv.org/pdf/2505.15049) (May 21 2025)
- [Against Generative UI, Okopnyi et al.](https://dl.acm.org/doi/epdf/10.1145/3686169.3686184) (Oct 21 2024)
- [pix2code: Generating Code from a Graphical User Interface Screenshot, Tony Beltramelli](https://arxiv.org/pdf/1705.07962) (May 22 2017)
### Videos (sorted by most recent)

- [Generative UI for any agent, anywhere: A2UI, AG-UI, MCP Apps, and more, Google Cloud Next 2026 Talk](https://www.youtube.com/watch?v=UsMDkEsR-ok) (Jun 25 2026)
- [Beyond Components: Designing Generative UI for MCP Apps, AI Engineer 2026 Ruben Casas with Postman](https://www.youtube.com/watch?v=hCMrEfPG2Yg) (Jun 3 2026)
- [MCP UI: Extending the frontier — Liad Yosef and Ido Salomon, MCP Apps](https://www.youtube.com/watch?v=o-zkvb0iFDQ) (May 6 2026)
- [Generative UI Spectrum - The Three Flavors, Tyler Slaton (CopilotKit)](https://www.youtube.com/watch?v=y4lln0yGMSE) (Apr 27 2026)
- [Generative UI: Specs, Patterns, and the Protocols Behind Them (MCP Apps, A2UI, AG-UI), CopilotKit](https://www.youtube.com/watch?v=Z4aSGCs_O5A) (Jan 30 2026)
- [How to implement generative UI without losing control - Chromatic with Michael Magan, Co-creator of Tambo](https://www.youtube.com/watch?v=5DIM5uHMMjI) (Jan 29 2026)
- [Gemini 3 and Gen UI in Google Search](https://www.youtube.com/watch?v=AqyclkRBSe4) (Dec 18 2025)
- [Generative user interfaces, Mike Ryan with Hashbrown](https://www.youtube.com/watch?v=ekQ7t6_MvOQ) (Jul 17 2025)
- [Real-Time UI Generation: Building Dynamic Web Experiences with GenUI, Adam Lucek](https://www.youtube.com/watch?v=zCGzM0JxvRg) (May 5 2025)
- [Build a Generative UI App in LangGraph](https://www.youtube.com/watch?v=sCqN01R8nIQ) (Mar 13 2025)
- [Stanford Seminar - Generative, Malleable, and Personal User Interfaces -- Haijun Xia, UC San Diego](https://www.youtube.com/watch?v=MbWgRuM-7X8) (Feb 25 2025)
- [Building Generative UI with Next.js](https://www.youtube.com/watch?v=cIzsQBbZNxk) (Nov 3 2023)

### Articles & Posts (sorted by most recent)
- [2030-shaped Software, Posthog](https://x.com/posthog/status/2079610793138823512) (Jul 22 2026)
- [Generative UI is the New Frontend](https://x.com/Saboo_Shubham_/status/2062220865643982875) (Jun 4 2026)
- [Generative UI: A rich, custom, visual interactive user experience for any prompt, Google Research](https://research.google/blog/generative-ui-a-rich-custom-visual-interactive-user-experience-for-any-prompt/) (Nov 18 2025)
- [Malleable Software, Geoffrey Litt](https://www.inkandswitch.com/essay/malleable-software/) (Jun 2025)
- [Generative UI and Outcome-Oriented Design, Kate Moran & Sarah Gibbons (NN/g)](https://www.nngroup.com/articles/generative-ui/) (Mar 2024)
- [Introducing AI SDK 3.0 with Generative UI, Vercel](https://vercel.com/blog/ai-sdk-3-generative-ui) (Mar 2024)

## Apps
These are apps/websites/demonstrations whose main feature or value proposition revolves around generative UI.
- [Monogram](https://www.monogram.ai/) - A general purpose AI app that focuses on visual interfaces.
- [Posthog AI](https://posthog.com/ai) - Posthog's AI chat can generate dynamic interfaces
- 

## Contributing

Contributions welcome! Please read the [contribution guidelines](contributing.md) before opening a pull request.

## License

[CC0 1.0](license)
