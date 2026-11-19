# ARCANEAIOS — LEOOS V4

V4 interface foundation for the ARCANE private operating environment.

## Current state
- Premium responsive command-centre interface.
- Four-wing navigation and the V3 room registry (20 rooms + Trading annex).
- Floor overview for four ventures and the 19-agent roster.
- Agent Operations, Intelligence Exchange, War Room, Knowledge Graph and Control Room shells.
- Local task creation, completion, deletion and daily objective persistence using browser localStorage.
- Explicit readiness indicators: V3 database/API and AI providers are not connected in this V4 repository yet.

## Run locally
This is a static front-end and can be previewed with any static server. For example:

```bash
python3 -m http.server 4173
```

Then open http://localhost:4173.

## Important
This is the first V4 interface implementation, not a replacement for the V3 backend. The next integration phase is to bring across the existing V3 packages, API, database client, brain and tests into this repository, then replace local-only operational state with the existing API/store boundaries. No provider is represented as connected and no API key is stored in browser code.

## Standing rules
- No unrestricted agent permissions.
- No autonomous spending.
- No unattended publishing.
- Notion remains read-only.
- Every execution must be traceable.
- Database writes must follow existing permission boundaries.
