# Preview builds for documentation changes

## Why this matters
If reviewers can’t see changes rendered, reviews degrade to grammar feedback.

Preview builds shift reviews from *text* to *experience*.

## Minimal setup
- Build docs on every PR
- Publish to a temporary URL
- Link preview in the PR description

## Review workflow
1. Author opens PR
2. CI builds preview
3. Reviewer checks:
   - structure
   - navigation
   - scannability
   - accuracy in context
4. Merge

## What this prevents
- “LGTM” without reading
- Late-stage layout surprises
- Merging broken navigation

## My default
If docs-as-code exists, preview builds are non-negotiable.

## Failure modes
- Previews that are slow
- Previews that require local setup
- Previews reviewers ignore

## Checklist
- Can a reviewer click once and see changes rendered?
- Is the preview clearly labeled as non-prod?
