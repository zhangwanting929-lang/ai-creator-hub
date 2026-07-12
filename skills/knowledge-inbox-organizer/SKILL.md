---
name: knowledge-inbox-organizer
description: Turn screenshots, links, transcripts, files, rough notes, chat records, and project observations into clean, linked Markdown knowledge for an Obsidian-style vault. Use this skill whenever the user asks to collect, organize, archive, summarize, connect, or write incoming information into a personal knowledge base, even if they only say "put this in my notes" or provide raw material without naming Obsidian.
---

# Knowledge Inbox Organizer

Convert raw information into durable, traceable knowledge without losing the source or inventing facts.

## Intake

1. Identify the source type: screenshot, link, transcript, document, idea, project experience, user question, or external information.
2. Preserve the source path or URL and capture the date when available.
3. If the material is incomplete or unreadable, record the limitation instead of filling gaps from assumption.

## Understand

Separate the material into:

- Facts supported by the source
- Opinions or interpretations
- Reusable insights
- Questions that remain unresolved
- Actions with a clear owner or next step

Write a one-sentence summary before expanding the note. This forces the note to have a clear purpose.

## Choose a destination

Prefer the user's existing vault structure. When no structure is defined, use:

- `00-输入池`: raw or unresolved information
- `10-项目`: work with a defined outcome or end condition
- `20-领域`: topics and responsibilities maintained over time
- `30-资料`: reusable reference knowledge
- `35-内容引擎`: publishable ideas, scripts, articles, and content assets
- `50-复盘`: results, evidence, lessons, and rule changes
- `40-归档`: inactive or completed material

Do not create a new category when an existing one fits. Leave ambiguous material in the inbox with a clear status.

## Write the note

Use this structure unless the vault already has a stronger local template:

```markdown
---
created: YYYY-MM-DD
source:
status: 已提炼
tags: []
---

# Title

## 一句话摘要

## 核心内容

## 可复用价值

## 关联笔记

## 下一步行动
```

Keep titles concrete and searchable. Use internal links to connect existing notes. Prefer one strong note over several thin, repetitive notes.

## Protect private information

Before writing into a public or Git-backed location, remove customer data, account credentials, API keys, private contact details, internal company data, and copyrighted source files that the user has not authorized for publication.

When the destination's visibility is unclear, treat it as private and state that assumption.

## Finish

Report:

- The note created or updated
- Its destination category
- Important links added
- Any unresolved question or action

Do not claim that a note was linked, synced, or published without verifying the resulting file or remote state.

