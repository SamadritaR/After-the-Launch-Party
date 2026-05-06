# After the Launch Party — Company Reference

*A companion document to the project. What each of the 30 companies is, and how they're leveraging AI.*

**Project thesis:** Scoring 60 AI features from 30 companies (15 AI native, 15 traditional SaaS) to answer: which features stuck six months after launch, and what patterns separate the survivors from the shelved?

**How to read this doc:** For each company, you get three things. One, what the company fundamentally is. Two, how they're using AI right now. Three, a brief "why they're on this list" note tying back to the project. This is a reference you'll glance at throughout the research phase, so it's deliberately scannable rather than exhaustive.

**Version:** v1.0, April 2026. Iterate as the project evolves.

---

## Group A, AI Native (15 Companies)

These companies were born after the GenAI wave. Strip out the AI, and the product collapses.

---

### 1. OpenAI (ChatGPT)

**What it is:** The company that built ChatGPT, the product that effectively kicked off the consumer GenAI wave in November 2022. OpenAI makes large language models (GPT 4, GPT 5) and packages them into consumer and enterprise products such as ChatGPT, the API platform, custom GPTs, and increasingly, agent like tools.

**How they leverage AI:** AI is the entire product. ChatGPT is a conversational interface to a frontier model, with steadily expanding capabilities: chat, voice mode, image generation, web search, memory, custom GPTs, canvas for collaborative editing, and agent tools that can execute multi step tasks.

**Why they're on this list:** You cannot write a playbook about post ChatGPT AI features without studying ChatGPT itself. Their feature decisions set expectations for every other product in the dataset. If Memory works, everyone ships memory. If Canvas flops, everyone quietly drops similar features.

---

### 2. Anthropic (Claude)

**What it is:** An AI safety company founded by former OpenAI researchers, now one of the two or three most important AI labs in the world. Claude is their flagship assistant product, positioned as a more thoughtful, enterprise ready alternative to ChatGPT, with particular strengths in long context reasoning, coding, and writing.

**How they leverage AI:** Like OpenAI, AI is the product. Claude ships as a chat interface, an API for developers, and inside a growing set of product integrations. Notable features include Artifacts (generative UI that renders in chat), Projects (persistent context workspaces), Computer Use (agents that operate a computer), and Claude Code (an AI coding assistant that runs in the terminal).

**Why they're on this list:** Including Claude alongside ChatGPT lets you directly compare two different philosophies of "what a chat product should be." Anthropic is also a direct target employer on your sheet, which means serious engagement with their features doubles as company research for interviews.

---

### 3. Perplexity

**What it is:** An AI native search engine that positions itself as a direct replacement for Google for many kinds of questions. Instead of returning a list of links, Perplexity reads the web in real time and synthesizes a cited answer.

**How they leverage AI:** Every core interaction is AI mediated. Features include Quick Search (fast cited answers), Deep Research (longer, structured reports), Spaces (workspaces with persistent context), Pages (shareable AI generated documents), and Comet (an AI native browser that Perplexity launched to extend their interface beyond search).

**Why they're on this list:** Perplexity is the cleanest example of an AI native product built specifically to replace a legacy category. Every feature they ship is a bet that a fundamentally new interaction model can beat a twenty year old incumbent.

---

### 4. Glean

**What it is:** An enterprise AI search and knowledge management platform. Glean connects to all the apps a company uses (Gmail, Slack, Google Drive, Jira, Notion, Salesforce) and provides a single AI powered search and chat interface across everything.

**How they leverage AI:** AI is central to the entire product. Glean's features include universal search across apps, AI generated answers grounded in company content, custom workplace agents, and increasingly, a platform for building domain specific AI assistants for HR, sales, engineering, and other functions.

**Why they're on this list:** Glean represents the "AI for work" category done well and at scale. Including Glean tests whether the playbook generalizes from consumer to enterprise, and sets up a direct comparison with Dropbox Dash, which is chasing a similar thesis from the incumbent side.

---

### 5. Cursor

**What it is:** An AI native code editor forked from VS Code, built by Anysphere. Cursor is what you use if you want to write code with an AI assistant that can read your entire codebase, make multi file edits, and increasingly work as an autonomous agent.

**How they leverage AI:** AI is the reason to use Cursor over VS Code. Features include tab completion on steroids (Cursor Tab), Composer (multi file edits via natural language), Agent mode (autonomous task execution), Bug Finder, and integrations with frontier models like Claude and GPT for different tasks.

**Why they're on this list:** Cursor is the single most beloved AI developer tool of this wave, with genuinely strong retention signals. It functions as a benchmark in the dataset. Many other features will compare unfavorably to Cursor's obvious product market fit.

---

### 6. Harvey

**What it is:** A domain specific AI platform built for law firms and legal teams. Harvey uses LLMs fine tuned and scaffolded for legal work, including contract analysis, litigation research, diligence, and drafting.

**How they leverage AI:** AI is the entire product, specifically adapted for legal workflows. Harvey's features include legal research agents, contract review, drafting assistance, matter specific knowledge bases, and Harvey Workflows for automating routine legal tasks. Used by most major law firms globally.

**Why they're on this list:** Harvey tests an important thesis. Does a narrow, vertical AI product outperform general purpose ones in real knowledge work? It's also the only legal industry example in the dataset, which gives you category diversity. Your personal interest in Suits gives you an authentic angle no other candidate will have.

---

### 7. Jasper

**What it is:** A first wave AI content platform that launched in 2021, originally for AI assisted marketing copy. Post ChatGPT, Jasper has pivoted significantly and now positions itself as an "AI agent workspace for marketing teams," with more than 100 specialized marketing agents and end to end content pipelines.

**How they leverage AI:** Jasper's current positioning is agentic AI for marketing. Structured workflows take a campaign brief and produce on brand assets across channels (blog, social, ads, email). Brand Voice, Knowledge Base, and Content Pipelines are meant to keep output consistent. They've been LLM agnostic, switching models as frontier labs iterate.

**Why they're on this list:** Jasper is one of the most important *adaptation stories* in the dataset. They dominated a category that ChatGPT partially commoditized, and they've visibly pivoted. Studying how their features evolved is more interesting than studying a pure success. The playbook needs cautionary tales and comebacks alongside hits.

---

### 8. Writer

**What it is:** An enterprise generative AI platform focused on writing, analysis, and process automation for large companies. Writer positions itself as an end to end AI system for Fortune 500s, with its own family of models (Palmyra) and a strong emphasis on security, governance, and domain customization.

**How they leverage AI:** Writer's product includes AI apps for marketing, legal, HR, and engineering use cases, plus AI Studio (for building custom AI workflows) and Knowledge Graph (grounding AI on company content). Focus is enterprise: SSO, audit logs, compliance controls, hosted deployment options.

**Why they're on this list:** Writer is the perfect foil to Jasper. Same broad category (AI for content and knowledge work) but a completely different strategy (enterprise, custom models, deep integration). The contrast between Jasper and Writer is one of the project's built in comparisons.

---

### 9. Gamma

**What it is:** An AI native tool for creating presentations, documents, and web pages. You describe what you want ("a pitch deck for a Series A fintech startup"), and Gamma generates an editable, designed artifact rather than a ChatGPT text blob.

**How they leverage AI:** AI powers the entire creation flow. Features include AI generated decks from prompts, AI assisted editing (change tone, restructure, regenerate a section), template aware generation, and export to PowerPoint or PDF. Gamma sits between ChatGPT (text) and Canva (fully manual design).

**Why they're on this list:** Gamma represents the "AI as creative collaborator" category, distinct from chat and distinct from search. You've used it personally, which means you can score its features from real experience rather than pure research.

---

### 10. Descript

**What it is:** An AI native video and audio editing tool. Descript's core innovation is editing video by editing the text transcript. Delete a sentence, and the corresponding video cuts disappear automatically.

**How they leverage AI:** AI is central. Features include Overdub (voice cloning to fix or add audio without re recording), Studio Sound (remove background noise, improve voice quality), AI Eye Contact (fixing gaze direction), Auto Edit (remove filler words and long pauses), and AI effects across video and audio.

**Why they're on this list:** Descript represents AI applied to creative workflows, a different category from writing or search. You've used it personally. Including it gives the dataset diversity beyond text based AI and sets up a natural comparison with Runway.

---

### 11. Runway

**What it is:** An AI native creative platform focused on video generation, editing, and visual effects for filmmakers, marketers, and content creators. Runway has shipped some of the most advanced video generation models publicly available (Gen 3, Gen 4) and has Hollywood level users.

**How they leverage AI:** Generative AI is the product. Features include text to video, image to video, video to video style transfer, Act One (capture actor performances and transfer them to characters), Motion Brush (directing motion in generated video), and a growing set of controllable video tools.

**Why they're on this list:** Runway's video features are among the most ambitious user facing AI products of the wave. It's also a rare case of a consumer or prosumer AI product in a sea of B2B ones, which gives the dataset audience diversity.

---

### 12. ElevenLabs

**What it is:** The clear category leader in AI voice synthesis and voice cloning. ElevenLabs' models can generate extremely natural speech in dozens of languages, clone a voice from a short sample, and provide voice infrastructure to apps, audiobook publishers, game studios, and dubbing companies.

**How they leverage AI:** Voice AI is the product. Key features include text to speech with expressive voices, instant voice cloning, voice library (licensed voices for commercial use), Dubbing (translating videos while preserving the original speaker's voice), Projects (long form audio creation), and Conversational AI for real time voice agents.

**Why they're on this list:** Voice AI has very different adoption dynamics than text AI. Different use cases, different user types, different decay curves. Including ElevenLabs gives the dataset a voice category anchor, which lets you make cross modality comparisons.

---

### 13. Character.ai

**What it is:** A consumer AI platform where users create and chat with AI generated characters, including historical figures, fictional characters, or original creations. At its peak, Character.ai had massive Gen Z engagement and some of the longest session times of any consumer AI product.

**How they leverage AI:** Character chat is the core product, powered by custom in house models. Users can create characters (define personality and context), chat in ongoing conversations, and join community spaces. The company has been through significant turbulence, including founder departures to Google, legal issues around minor users, and strategic pivots.

**Why they're on this list:** Character.ai gives the dataset the consumer AI companion angle, which no other company covers. The decline and controversy make it a genuinely rich case study for "what happened after launch," including the risks of shipping without adequate safeguards. Studying it evenhandedly (measuring, not moralizing) is itself a PM skill.

---

### 14. Replit

**What it is:** A browser based coding environment that lets anyone build and deploy software without installing anything locally. Replit started pre GenAI but has aggressively repositioned around AI assisted and AI autonomous coding.

**How they leverage AI:** Replit Agent is their flagship AI feature. You describe an app in natural language and the agent builds it, asking for input as needed. They also have Ghostwriter (AI pair programming), AI debugging, and AI assisted deployment. Replit's bet is that AI lets non engineers build real software.

**Why they're on this list:** Replit straddles both sides of the AI native and traditional divide. It existed pre GenAI but was built on AI native assumptions (browser first, collaborative, accessible). This makes it a useful test case for companies navigating the transition.

---

### 15. Granola

**What it is:** An AI notepad for meetings, headquartered in London. Unlike meeting bots that join calls visibly, Granola runs locally on your computer, transcribes meeting audio without joining the call, and combines its transcript with the bullet points you type to produce structured notes.

**How they leverage AI:** AI is central to the entire product. Features include local transcription (no visible bot), AI enhanced note generation, Chat with Notes (query your own meeting history), Spaces (team workspaces with shared folders), Slack integration, and a Model Context Protocol server plus APIs that let other AI tools (Claude, Cursor, Figma) read Granola's context. Recently raised $125M at $1.5B valuation (March 2026), pivoting from individual tool to enterprise AI context layer.

**Why they're on this list:** Granola gives the dataset freshness. Its launch trajectory is still unfolding, which means "six months after launch" is genuinely unresolved. It's also currently beloved by PMs and founders, which makes it a referenceable example in cold emails. The enterprise pivot is a live strategic bet worth studying.

---

## Group B, Traditional SaaS (15 Companies)

These companies existed and were successful before the GenAI wave. Their AI features are bolted onto established products with existing users.

---

### 16. Notion

**What it is:** An all in one workspace for notes, docs, wikis, databases, and project management. Notion launched in 2016 and grew into one of the most loved productivity tools in tech, especially among startups and knowledge workers.

**How they leverage AI:** Notion added AI progressively, starting with Notion AI (writing assist, summarization) in early 2023 and expanding into Q&A (ask questions across your workspace), AI powered database autofill, AI meeting notes, and AI search. Their bet is that AI turns Notion from a place where you *store* knowledge into a place where knowledge *works for you*.

**Why they're on this list:** Notion AI is the most discussed AI bolt on in the productivity category, with multiple named sub features launched at different times. This is one of the few companies where you'll have to choose *which* AI feature to focus on, and that choice itself is informative. Notion is also on your target company sheet.

---

### 17. Slack

**What it is:** The enterprise messaging platform, now owned by Salesforce. Slack is where work conversation happens at most modern companies through channels, DMs, threads, and integrations with everything.

**How they leverage AI:** Slack AI is the flagship AI product, sold as a premium add on. Core features include channel and thread summaries, search answers, daily recaps, and increasingly, AI agents that can act across Slack. With Salesforce ownership, Slack AI is also a delivery surface for Agentforce agents.

**Why they're on this list:** Slack AI is a flagship bet from Salesforce and central to their enterprise AI strategy. It's one of the few AI features with clear paid tier pricing, which makes pricing and adoption signal unusually measurable. You can literally see whether customers are paying for it.

---

### 18. Asana

**What it is:** A work management platform for teams, including tasks, projects, timelines, and workflows. Asana is a category leader in project management SaaS for mid market and enterprise.

**How they leverage AI:** Asana Intelligence is their AI layer, including smart goals, smart status (AI generated project updates), smart fields, smart summaries, and AI Studio for building custom workflow agents. The positioning is "AI that does the project management busywork so humans can focus on execution."

**Why they're on this list:** Asana lets you test whether project management AI features are genuinely used or mostly demo ware. The comparison with the other PM adjacent tools in the dataset (Linear, Miro) is where the category insight emerges.

---

### 19. Linear

**What it is:** A premium issue tracking and project planning tool, especially beloved by engineering and product teams at high growth startups. Linear is known for its design quality, keyboard first UX, and disciplined product culture.

**How they leverage AI:** Linear has been characteristically restrained with AI. Rather than shipping everything at once, they've added targeted AI: auto generated issue descriptions, AI triage suggestions, smart search, and more recently, Linear Agents (AI that can act on issues). Their philosophy is "AI should reduce friction, not add buttons."

**Why they're on this list:** Linear is important because their product culture is "ship less, ship better." Studying how a disciplined company approaches AI is a direct counterpoint to the "ship everything" approach of bigger companies. Linear is also on your target list.

---

### 20. Figma

**What it is:** The dominant collaborative design tool, used by design teams at virtually every modern tech company. Figma is where UI and UX design, prototyping, and design systems live.

**How they leverage AI:** Figma AI includes features for generating designs from prompts, auto organizing and renaming layers, visual search across your design files, and AI assisted prototyping. Famously, Figma *publicly paused* Make Designs shortly after launch in 2024 when outputs too closely resembled existing apps. One of the most visible AI feature retreats of the wave.

**Why they're on this list:** Figma had one of the most public AI failures and course corrections of the wave. Few other features have documented post launch retreats as clearly as Figma AI did, which makes it one of the richest single stories in the dataset.

---

### 21. Canva

**What it is:** A consumer and SMB design platform with over 200 million users worldwide. Canva is where non designers make social posts, presentations, flyers, videos, and more.

**How they leverage AI:** Canva Magic Studio is the umbrella for their AI features. Magic Design (generate designs from prompts), Magic Write (AI copy), Magic Media (AI image, video, and graphic generation), Magic Edit (AI photo editing), Magic Switch (resize and reformat), and Magic Resize. Canva also has a Visual Suite pitched at teams.

**Why they're on this list:** Canva is one of the few consumer scale AI rollouts on the list. Shipping AI to more than 200M users, most of whom are non technical, creates very different adoption dynamics than B2B AI, which gives the dataset audience diversity.

---

### 22. HubSpot

**What it is:** A CRM and marketing platform for SMBs and mid market companies. HubSpot covers marketing automation, sales pipeline, customer service, CMS, and operations.

**How they leverage AI:** Breeze is HubSpot's AI layer, introduced in 2024. Breeze includes Breeze Copilot (in product AI assistant), Breeze Agents (AI for content creation, prospecting, social, customer service), and Breeze Intelligence (enriched data and buyer intent signals). Positioning: "AI to help SMBs punch above their weight."

**Why they're on this list:** HubSpot is publicly aggressive about AI positioning and has shipped many named features quickly, which makes it a useful test case for the "fast shipping versus sticky features" question.

---

### 23. Salesforce

**What it is:** The largest enterprise SaaS company in the world, with CRM, Sales Cloud, Service Cloud, Marketing Cloud, and many other products. Also owns Slack and Tableau.

**How they leverage AI:** Salesforce has the most ambitious enterprise AI bet on this list. Einstein is their longstanding AI layer (predictions, recommendations), and Agentforce is their newer agent platform, offering pre built and custom AI agents that can act across Salesforce and beyond. Einstein GPT, Einstein Copilot, and Einstein Studio round out the portfolio.

**Why they're on this list:** Salesforce's AI strategy includes both bolt on features and a major platform push (Agentforce). The scope lets you study a company that tried multiple AI strategies in parallel, a pattern that will recur across other incumbents.

---

### 24. Zoom

**What it is:** The video conferencing platform that became a household name during COVID. Zoom has expanded beyond meetings into phone, chat, contact center, and collaboration.

**How they leverage AI:** Zoom AI Companion is included free with most paid Zoom plans, unusual in a market where AI features are usually paid add ons. Features include meeting summaries, smart recordings with chapters and action items, chat compose, meeting Q&A, email and calendar drafting, and an AI Companion that works across Zoom's product suite.

**Why they're on this list:** Zoom is important because meetings AI is a hot category (Otter, Fireflies, Granola, and many others all compete). Zoom has distribution advantage. Their AI is free to existing customers. Testing whether distribution beats product quality is one of the project's latent questions.

---

### 25. Intercom

**What it is:** A customer messaging and support platform used by thousands of businesses. Intercom is the inbox, chatbot, help center, and CRM for many B2B SaaS companies.

**How they leverage AI:** Fin is Intercom's AI customer support agent, arguably the single most successful traditional SaaS AI feature on this list. Fin resolves customer questions autonomously, grounded on a company's help content, with publicly shared metrics on resolution rates (often 50% or higher) and cost savings. Intercom has also repositioned the entire company around Fin.

**Why they're on this list:** Every project needs at least one clear success story to anchor the "what good looks like" patterns. Fin is that anchor. Its adoption, pricing (charge per resolution), and public customer outcomes are unusually transparent for AI features, which makes scoring it unusually clean.

---

### 26. Atlassian

**What it is:** The parent company of Jira (issue tracking), Confluence (wiki and docs), Trello (boards), Bitbucket (code), and more. Atlassian is the default stack for engineering and technical project management at most modern enterprises.

**How they leverage AI:** Atlassian Intelligence is the AI layer across all their products, offering AI search, summarization, AI assisted writing in Confluence, AI generated Jira issues, and automation suggestions. Rovo is their newer, more agentic product, a standalone AI work assistant that connects to Atlassian and third party tools.

**Why they're on this list:** Atlassian represents the "AI layered across an existing platform" strategy, its own archetype. Rovo adds an agentic and platform angle that compares interestingly with Salesforce Agentforce and Glean.

---

### 27. Airtable

**What it is:** A spreadsheet and database hybrid that lets non engineers build lightweight apps and workflows. Airtable sits between Excel and a full database, used for everything from content calendars to CRMs to inventory management.

**How they leverage AI:** Airtable AI includes AI fields (apply AI to any column to summarize, categorize, translate, extract), Cobuilder (AI builds an Airtable app from a prompt), and AI agents that operate on base data. The positioning: "AI that works on your structured data, not just your text."

**Why they're on this list:** Airtable represents AI applied to databases and structured data, a fundamentally different category from text or chat AI. Structured data AI has underexplored adoption dynamics, which makes Airtable one of the more original entries in the dataset.

---

### 28. Miro

**What it is:** An online whiteboard platform for visual collaboration, including brainstorming, planning, diagramming, workshops, and remote first meetings.

**How they leverage AI:** Miro AI includes auto clustering sticky notes, summarization of whiteboard content, AI generated diagrams (from prompts), AI generated mind maps, presentation generation, and Intelligent Canvas features. Miro's approach has been to ship many small AI features rather than one big one.

**Why they're on this list:** Miro tests the "AI for whiteboarding and visual collaboration" category, which sits between writing AI and design AI. The many small features approach is its own archetype. It lets you score feature per feature rather than product wide, which gives you more data points.

---

### 29. Grammarly

**What it is:** A writing assistant that lives as a browser extension, desktop app, and mobile keyboard. Grammarly has been around since 2009, originally as a grammar and spell checker, now positioned as an AI powered communication assistant.

**How they leverage AI:** Grammarly rebuilt its entire product around LLMs post ChatGPT. Generative AI features include rewriting, tone adjustment, content generation, summarization, and AI powered suggestions across 500,000 or more apps and sites. The company has made explicit strategic bets on being the embedded AI writing layer that works everywhere you already write.

**Why they're on this list:** Grammarly is uniquely positioned. A pre GenAI ML product that had to rebuild around GenAI or be eaten by ChatGPT. It's the only "successful re platforming" story in the dataset, and it's the only company that had to *defend* an AI adjacent market.

---

### 30. Dropbox (Dash)

**What it is:** The file sync and share company with more than 700M registered users and 18M paid users, now publicly betting its future on AI. Dropbox's original product (cloud storage) is mature and commoditized. Dash is their attempt to become an AI layer for work.

**How they leverage AI:** Dropbox Dash is the flagship AI product, a universal search and knowledge management tool that connects to Google Drive, Slack, Microsoft 365, Notion, Canva, Jira, and other apps. Features include natural language search across all connected apps (including video and image content), AI generated answers with citations, AI writing tools, Stacks (living team workspaces), and an MCP server that lets Dash plug into Claude, Cursor, and other AI clients. Dash is available standalone or embedded in the familiar Dropbox interface.

**Why they're on this list:** Dropbox is one of the clearest "old company reinventing itself around AI" stories, an unusual and important case type that no other company on the list represents as sharply. The company's 2025 revenue guidance was publicly raised on the strength of Dash adoption, giving you rare financial evidence of how a traditional SaaS AI bet is performing.

---

## Quick scan summary by category

For fast navigation during the research phase.

- **General chat and assistants:** OpenAI/ChatGPT, Anthropic/Claude
- **Search and knowledge discovery:** Perplexity, Glean, Dropbox Dash
- **Coding:** Cursor, Replit
- **Writing and content:** Jasper, Writer, Grammarly
- **Creative (design, video, audio, voice, presentations):** Figma, Canva, Gamma, Descript, Runway, ElevenLabs
- **Meetings:** Zoom, Granola
- **Customer support:** Intercom
- **Sales, marketing, and CRM:** HubSpot, Salesforce
- **Work, project, and productivity:** Notion, Slack, Asana, Linear, Atlassian, Airtable, Miro
- **Consumer AI companions:** Character.ai
- **Vertical (legal):** Harvey

---

## What this document is for

- Quick reference when scoring features. You can re read a company's paragraph in 60 seconds instead of re researching.
- Foundation for the final writeup's "companies studied" appendix.
- Study aid for interviews. Read one entry a day and you'll have fluent opinions on 30 AI products.
- Version controlled baseline. Update as companies ship new features or pivot.

## What this document is NOT

- An exhaustive product catalog. Each company has more features than listed here.
- A ranked evaluation. No scoring yet. That's the next phase of the project.
- A static artifact. Expect to update it as research deepens.
