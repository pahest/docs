# Pahest docs

The user guide of [Pahest](https://github.com/pahest/pahest), a local backup of Claude Code and Codex sessions on a Mac.

Read the guide at [pahest.revdoku.site](https://pahest.revdoku.site).

[Revdoku](https://revdoku.com) publishes the site from this repository. Each push to the `main` branch updates the site.

## Files

The guide is in the Mintlify format.

| File or folder | Content |
| --- | --- |
| `docs.json` | The name of the site, the colors, and the sequence of the pages. |
| `*.mdx` | One page each. The top of each file has the title and a description of one line. |
| `images/` | The screenshots, and `pahest-icon.png`, the icon with 512 pixels. |
| `favicon.png` | The icon of the site, 64 pixels. |

## Rules for the pages

- Tell the reader only how to use Pahest. Do not tell how Pahest works inside, and do not give instructions for other tools.
- Write Simplified Technical English (STE): short sentences, active voice, one word for one meaning, `can`, `will` and `must`. Software verbs such as `run`, `click`, `install` and `delete` are permitted.
- Each output block is real output of Pahest. Do not write output by hand. You can cut lines and put `…` in their place.
- Remove personal data from output. Write the user name as `you`, so that a home folder is `/Users/you`. Do not show names of projects, folders or sessions.
- When a new version of Pahest changes its text or its pages, run it again and replace the output and the screenshots.
- Use only these components: `Frame`, `Steps` and `Step`, `CardGroup` and `Card`.

## Source of the output

The output in this guide is from Pahest 0.1.3 on 2026-11-11.

| Page | Output | Source |
| --- | --- | --- |
| `first-backup` | The first and last lines of a run | A real backup of a Mac with about 1,050 sessions. |
| `commands` | The options, the rebuild | The same Mac and the same backup. |
| `commands`, `backups-folder`, `problems` | The profile, the folder question, the messages | A test home folder with one small session. |
