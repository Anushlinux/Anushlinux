# Anushrut Pandit

I’m a product engineer in Mumbai, currently building
[Smalltalk](https://github.com/Anushlinux/smalltalk): an open-source, local-first
macOS app for returning to interrupted work.

Smalltalk reconstructs the task you were working on, the point you reached, and
a safe next step from sparse local evidence. When it cannot support an answer,
it says so instead of inventing one.

[Download the latest macOS build](https://github.com/Anushlinux/smalltalk/releases/latest)
· [Explore the Smalltalk source](https://github.com/Anushlinux/smalltalk)

## What I’m building now

I’m extending Smalltalk from one-off interruption recovery into a small,
self-maintaining task system. The current prototype work includes:

- A durable local task list with explicit history and restart-safe state.
- Continue answers bound to one task and that task’s own evidence.
- Shadow proposals that can suggest changes without touching the visible list.
- Tightly gated automation that remains observational until real-world accuracy
  is proven.

The rule underneath all of it is simple: captured activity is evidence, model
output is a proposal, and neither becomes task truth without local validation.

## How it is built

Smalltalk spans **Rust and Tauri** for the desktop runtime, **Swift** for the
native macOS layer, **React and TypeScript** for the app, **SQLite** for local
state, and **Cloudflare and Supabase** for the optional hosted path.

I care about precise product behavior: safe defaults, inspectable decisions,
and systems that admit when they do not know.

## Elsewhere

[Anushrut on X](https://x.com/Anushlinux) ·
[Anushrut on LinkedIn](https://www.linkedin.com/in/anushlinux)
