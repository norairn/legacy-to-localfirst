# legacy-to-localfirst

Convert legacy applications into local-first web apps.

## What is this?

`legacy-to-localfirst` is an experimental conversion pipeline for modernizing legacy desktop software — starting with Win32 applications — by transforming them into local-first web applications.

Instead of rewriting from scratch, it analyzes existing UI structures (menus, commands, dialogs) and generates:

- Application specification (AppSpec)
- Object-system domain model
- Local persistence schema
- View metadata (ViewMeta)
- Runnable local-first project skeleton
- Capability backlog for incremental migration

## Why local-first?

Local-first apps:

- Work offline by default  
- Sync when connectivity is available  
- Provide instant performance  
- Preserve user data ownership  
- Enable resilient multi-device workflows  

## Pricing philosophy

- **Free**: convert and run apps locally, offline  
- **Paid**: enable sync, sharing, and multi-device collaboration  

You own your data. The network is optional.

## Current scope

- Win32 desktop apps (initial focus)  
- Menu & command extraction  
- Document-centric apps (e.g., Notepad)  
- IndexedDB/Dexie persistence  
- Object-system UI architecture  

## Status

Early-stage / experimental.

## License

MIT
