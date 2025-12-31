# When docs-as-code is worth it

**Default:** docs-as-code is worth it when you have a reliable PR review culture and frequent changes.

## Good fit signals
- You ship frequently (weekly+)
- Engineers already work in Git
- You need previews, versioning, and review trails
- You have recurring doc debt due to “unowned pages”

## Bad fit signals
- No one reviews PRs in time
- Content is mostly marketing pages (heavy CMS workflows)
- Your organization can’t tolerate “merge queue” delays

## The tradeoff that matters
Docs-as-code optimizes for **traceability and scale**, but it introduces **process friction**.

## My default
- Start docs-as-code for **technical reference + release docs**
- Keep marketing content in a CMS if needed
- Add preview builds early (so review is visual)

## When I override the default
- If writers can’t ship without engineering help, start in a CMS first, then migrate.

## Checklist
- Can a non-engineer safely open a PR?
- Do you have preview builds?
- Who is the DRI for doc build failures?
