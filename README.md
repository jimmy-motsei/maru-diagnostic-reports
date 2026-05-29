<!-- MARU SYSTEM STATUS: 🟢 live | maru-diagnostic-reports | https://maru-diagnostic-reports.vercel.app -->
# maru-diagnostic-reports

Static HTML repository for Maru Online client diagnostic reports.

## Structure

```
clients/
  [client-slug]/
    index.html    — self-contained diagnostic report
```

## Adding a new diagnostic

1. Create a new folder under `clients/` using a kebab-case slug matching the client name
2. Add the self-contained `index.html` diagnostic file
3. Add a route entry to `vercel.json` for the new client path
4. Add the client to the root `index.html` index
5. Commit and push — Vercel auto-deploys from main

## Deployment

Hosted on Vercel. Auto-deploys on push to `main`.
Each client diagnostic is accessible at:
`https://maru-diagnostic-reports.vercel.app/clients/[client-slug]`

## Versioning

When a diagnostic is updated (v2, v3), update the file in place and update the
version reference in the root `index.html`. Git history preserves all previous versions.

## Stack

Pure static HTML. No build step. No framework. No dependencies.
