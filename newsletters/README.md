# Newsletter issues

This folder is the source of truth for newsletter issues. Each issue is written
and committed here first — reviewed and versioned like any other change to
this repo — before it's copy-pasted into Substack and sent.

## Workflow

1. Copy `_template.md` to a new file named `NNNN-slug.md` (e.g. `0001-a-chatbot-walks-into-the-agora.md`),
   incrementing `NNNN` from the last issue.
2. Write the issue in Markdown.
3. Commit and open a PR (or push directly, if working solo).
4. Once it reads the way you want, copy the rendered content into a new
   Substack draft and publish/send from there.
5. After sending, add the live Substack URL to the issue's frontmatter
   (`substackUrl:`) so the repo keeps a record of where it was published.

Substack has no public API for programmatic publishing, so step 4 is a manual
copy-paste — this repo exists to keep drafting, review, and history in git
rather than trusting Substack's editor as the only copy.
