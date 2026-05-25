# TimDesign_OS - Agent Instructions

## Purpose

This repository is the active AI-operable TimDesign_OS.

TimDesign is a premium web design and development business focused on high-end real estate and adjacent premium services in French-speaking Switzerland.

The goal is not to store everything. The goal is to help Tim run a stable, profitable, personally meaningful independent business.

Every change should support at least one outcome:

- generate revenue;
- clarify offers;
- improve sales or prospection;
- improve client delivery;
- strengthen positioning;
- create reusable templates;
- reduce cognitive noise;
- make TimDesign easier to execute.

## Source Of Truth

This GitHub/local repository is the active AI-operable OS.

Notion is the live operational workspace for projects, prospects, contacts, missions, statuses, and follow-up. If a task depends on live operational state, say that Notion may need to be checked.

Google Drive is old backup/reference material for this repo. Do not treat Drive as the active source of truth unless Tim explicitly says to resync from it.

Future AI agents should maintain this OS through Tim's natural-language instructions, keeping the repo small and directly useful.

## Core Principle

Be useful, not exhaustive.

Keep the OS small, active, navigable, and commercially useful. Do not preserve content just in case. Do not turn the OS into a library, archive, research dump, or meta-system.

## Active Structure

Use this structure:

- `00_INDEX.md`
- `00_Inbox/`
- `01_Strategy/`
- `02_Offers/`
- `03_Prospection/`
- `04_Clients/`
- `05_Templates/`
- `06_Content_AI/`
- `07_System/`

Create extra top-level folders only when they clearly reduce future maintenance.

## Index Rules

`00_INDEX.md` is a short human navigation entry point, not a raw file dump.

If a detailed inventory is useful, create `07_System/system_file_registry.generated.md`. Never overwrite the human-facing index with an exhaustive generated list.

## Cleanup Philosophy

This OS is intentionally more destructive than archival.

Keep files only when they are canonical, active, reusable, client-relevant, sellable, operational, strategically important, legally or financially important, or a current system rule.

Remove duplicates, obsolete variants, weak AI drafts, processed outputs, old logs, abandoned ideas, unclear notes, archive noise, and speculative material.

Prefer one strong canonical file over many partial variants.

Do not rebuild a permanent archive inside the active OS. Use Git history or an explicit external backup when safety is needed.

## Inbox Rules

`00_Inbox/` is temporary. Every inbox item should become an action in Notion, a canonical OS file, a reusable template, or be deleted.

If creating an inbox file, include why it exists and what should happen next.

## AI Content Rules

AI output is disposable by default.

Add AI-generated content only when it has a clear destination, concrete use, action value, and relationship to strategy, offers, prospection, clients, templates, content, or system rules.

Before adding content, ask:

- Does this replace something?
- Does this reduce noise?
- Does this help Tim act, sell, deliver, decide, or publish?
- Will this still be useful in 30 days?

If not, do not add it.

## Modification Rules

You may act directly on non-destructive improvements: clarify wording, improve structure, fix links, update indexes, merge obvious duplicates, simplify instructions, and create canonical files from scattered notes.

For destructive changes, prefer Git history, a clear cleanup record, or a branch/PR. Do not preserve old clutter inside the active OS just in case.

## Business Direction

When making judgment calls, bias toward:

- premium Webflow/web design and development;
- high-end real estate in French-speaking Switzerland;
- clear offers and stronger positioning;
- better sales and prospection;
- faster publishing;
- client delivery quality;
- recurring revenue where relevant;
- reducing meta-work.

## Tone

Prefer clear, concise, strategic, practical, premium-but-not-pompous, human-but-not-fluffy, commercially sharp writing.

Avoid corporate filler, fake certainty, motivational fluff, needless frameworks, excessive nesting, and giant reports.

## Definition Of Done

A task is done when the OS is clearer than before, fewer files compete as sources of truth, the index still works, active files are easier to use, Tim has less to maintain manually, and the result helps business execution.
