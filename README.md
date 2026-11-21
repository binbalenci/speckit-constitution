<div align="center">
  <img src="./icon.svg" width="112" alt="A document with five checkmarks" />
  <h1>speckit-constitution</h1>
</div>

A copy-ready constitution for GitHub Spec Kit. Five practical rules for planning changes, choosing architecture, testing behavior, and shipping in reversible steps.

## The five principles

1. Inspect Before Planning
2. Keep the Change Focused
3. Justify New Boundaries
4. Test at the Right Layer
5. Merge in Reversible Chunks

## Quick start

After initializing Spec Kit in your project, use its constitution command in your coding agent:

```text
/speckit-constitution Use https://raw.githubusercontent.com/binbalenci/speckit-constitution/main/constitution.md as the starting point for this project's constitution. Adapt the rules to this repo. If it already has a constitution, preserve the team's agreed rules and flag any conflicts. Show me the proposed changes before writing them to .specify/memory/constitution.md.
```

Use the command spelling your agent exposes; some integrations use `/speckit.constitution` instead. Review the proposed changes, resolve any conflicts, and tell your agent when to apply them.

### Or copy it yourself

Open [`constitution.md`](./constitution.md) and use **Raw** to copy the Markdown to `.specify/memory/constitution.md` in your project. Adapt it to your team's standards. If you already have a constitution, merge the rules that fit instead of replacing the file. Review the diff before merging.

### Check it on your first feature

Spec Kit reads your project's local `.specify/memory/constitution.md`. Your copy is yours to maintain; there’s no automatic sync. After adoption, run your integration's Spec Kit plan command on a feature and review `plan.md`'s **Constitution Check** for concrete checks against your rules and any gaps.

## Optional: Copy a specific version

Skip this section unless you want to remember exactly which version you started from.

1. Open [`constitution.md`](./constitution.md) on GitHub. Click the branch dropdown (usually **main**), choose **Tags**, and pick a version such as `v1.0.0`.
2. Copy the URL from your browser’s address bar. Give that link to your agent with the quick-start command, replacing the URL in the prompt. Or click **Raw** and copy the Markdown text on that page.
3. If copying yourself, paste the Markdown into `.specify/memory/constitution.md` in your own project. If that file already exists, copy in only the rules you want to adopt. If using your agent, review its proposed changes and tell it when to apply them.
4. Paste this line at the bottom of your local file. Replace `PASTE_URL_HERE` with the URL from step 2, and replace `v1.0.0` with the version you picked. If you copied the rules unchanged, use `Copied from` instead of `Adapted from`.

   ```markdown
   Adapted from [speckit-constitution contributors, v1.0.0](PASTE_URL_HERE) ([CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)).
   ```

If you want to update later, use that saved link to compare the old and new versions. Bring over the rules you want, update the source note, and open a pull request in your project for review.

## About and license

This is a community-maintained starting point for [GitHub Spec Kit](https://github.com/github/spec-kit). It is independent of GitHub and is not an official Spec Kit resource.

This repository's documentation is licensed under [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/legalcode.en). You can copy and adapt it, including for commercial use. When sharing a copy or adaptation, credit the speckit-constitution contributors, link to the source and license, and indicate any changes.

## Star history

[![Star history chart](https://api.star-history.com/chart?repos=binbalenci/speckit-constitution&type=date&legend=top-left)](https://www.star-history.com/?repos=binbalenci%2Fspeckit-constitution&type=date&legend=top-left)
