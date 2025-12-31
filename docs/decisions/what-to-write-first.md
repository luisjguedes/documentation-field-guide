# What to write first

**Default:** write the thing that unblocks a user action *today*.

Documentation often fails because teams start with what’s easiest to explain—not what users need to do.

## Options
**A) Task-first (how-to)**
- Best when users are trying to *do* something immediately.
- Fastest path to utility.

**B) Reference-first**
- Best when the product is an API/SDK or highly parameterized.
- Useful when users already know the workflow but need exactness.

**C) Concept-first**
- Best when misunderstanding is the main failure mode (complex domain, new mental models).

## Tradeoffs
- Task-first can become shallow if you never backfill concepts/reference.
- Reference-first can be technically perfect but useless without tasks.
- Concept-first can become vague and untestable.

## My default
**Start with one task page that removes friction** + a minimal reference stub for the same area.

## When I override the default
- **APIs:** start with reference + one end-to-end “hello world” task.
- **Regulated domains:** concept-first to align on definitions and constraints.

## Checklist
- Can a user complete a real action using only this page?
- Are the prerequisites explicit?
- Is the success state measurable?
