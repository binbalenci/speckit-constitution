A copy-ready constitution for GitHub Spec Kit. Five practical rules for planning changes, choosing architecture, testing behavior, and shipping in reversible steps.

## The five principles

1. Inspect Before Planning
2. Keep the Change Focused
3. Justify New Boundaries
4. Test at the Right Layer
5. Merge in Reversible Chunks

## Quick start: Copy and adapt

### Copy it yourself

Open [`constitution.md`](./constitution.md) and use **Raw** to copy the Markdown to `.specify/memory/constitution.md` in your project. Adapt it to your team's standards. If you already have a constitution, merge the rules that fit instead of replacing the file. Review the diff before merging.

### Ask your coding agent

Send your agent the link to [`constitution.md`](./constitution.md) along with this prompt:

```text
Read the constitution at the link I shared. Inspect this repo’s existing `.specify/memory/constitution.md` and project instructions. Propose how to adopt the shared rules while preserving the owning team’s agreed standards. Flag any conflicts and show me the proposed changes before editing.
```

### Verify your local copy

Spec Kit reads your project's local `.specify/memory/constitution.md`. Your copy is yours to maintain; there’s no automatic sync. After adoption, run your integration's Spec Kit plan command on a feature and review `plan.md`'s **Constitution Check** for concrete checks against your rules and any gaps.

## Optional: Copy a specific version

Skip this section unless you want to remember exactly which version you started from.

1. Open [`constitution.md`](./constitution.md) on GitHub. Click the branch dropdown (usually **main**), choose **Tags**, and pick a version such as `v1.0.0`.
2. Copy the URL from your browser’s address bar. Then click **Raw** and copy the Markdown text on that page.
3. In your own project, paste the Markdown into `.specify/memory/constitution.md`. If that file already exists, copy in only the rules you want to adopt.
4. Paste this line at the bottom of your local file. Replace `PASTE_URL_HERE` with the URL from step 2, and replace `v1.0.0` with the version you picked. If you copied the rules unchanged, use `Copied from` instead of `Adapted from`.

   ```markdown
   Adapted from [speckit-constitution contributors, v1.0.0](PASTE_URL_HERE) ([CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)).
   ```

If you want to update later, use that saved link to compare the old and new versions. Bring over the rules you want, update the source note, and open a pull request in your project for review.

## About and license

This is a community-maintained starting point for [GitHub Spec Kit](https://github.com/github/spec-kit). It is independent of GitHub and is not an official Spec Kit resource.

This repository's documentation is licensed under [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/legalcode.en). You can copy and adapt it, including for commercial use. When sharing a copy or adaptation, credit the speckit-constitution contributors, link to the source and license, and indicate any changes.
