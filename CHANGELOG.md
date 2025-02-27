# CHANGELOG

## 0.2.4

- infra: upgrade deps
- feat: support Logseq hash syntax

## 0.2.3

- fix: ref block cut issue
- chore: refactor some code

## 0.2.2

- feat: support auto wrap for long block.
- infra: upgrade deps.

## 0.2.1

- feat: ignore `---` lines
- feat: replace renderer lines

## 0.2.0

- feat: support export as svg

## 0.1.9

- feat: support block background color on markmap

## 0.1.8

- fix: pdf asset wrongly parsed as image on markmap.
- fix: optimize image parse, remove image properties.
- fix: can not load children blocks in recent Logseq release.
- infra: change from webpack to vite
- infra: upgrade deps

## 0.1.7

- fix: parse tag issue, should not parse url anchor

## 0.1.6

- feat: support exporting high resolution png.

## 0.1.5

- fix: remove shortcut `m m` but keep `ctrl+m ctrl+m`.
- feat: make the shortcut configurable.

## 0.1.4

- feat: support open page or block markmap in markmap.
- feat: support trigger backward on markmap.
- feat: support block page markmap trigger by shortcut.
- feat: add `cmd+[` and `cmd+]` shortcuts on markmap to traverse.

## 0.1.3

- feat: `m m`, Trigger Markmap for non-editing mode.
- feat: `ctrl+m ctrl+m`, Trigger Markmap for editing mode.
- feat: `Markmap` slash command.
- feat: `Markmap` contextual menu.
- feat: Editing block or highlighting block will be the central node of the Markmap, otherwise it will use the whole page blocks.
- fix: Local images can not popup after changing graph.

## 0.1.2

- feat: Add a block property `mark-map-limit:: N` to limit block next level block list items.
- feat: Add a page property `mark-map-limit:: N` to limit first level block list items.
- feat: Add a page property `mark-map-limit-all:: N` to limit all block list items.
- feat: Support parse block ref link and page ref link, eg. `[]((()))` and `[]([[]])`

## 0.1.1

- feat: Add a close button on right top corner and hidden by default.
- feat: Add a block property `mark-map-cut:: 30` to cut text length.
- feat: Add page property `mark-map-collapsed:: extend` to show all nodes, and ignore collapsed state.
- feat: Make mindmap show collapsed state the same with Logseq by default.
- fix: Local image lightbox not work on Windows.

## 0.1.0

- feat: Custom center node by setting page property `mark-map-title:: blahblah`
- feat: Hide any collapsed node by setting page property `mark-map-collapsed:: hidden`
- feat: Hide any node by setting block property `mark-map-display:: hidden`
- feat: Support multiline text by leading `- `
- feat: Support images opened in a popup modal using Lightbox2.
- fix: Local image can not be opened.

## 0.0.10

- feat: Support highlight syntax, `==` in Markdown mode, `^^` in Org mode.
- feat: Support Logseq block reference. #5
- feat: Support Logseq embed block reference.
- feat: Support Logseq page reference.
- feat: Support Logseq embed page reference.
- feat: Support Logseq page tag
- feat: Colorize workflow tags.

## 0.0.9

- no new features or bug fixes, just fix meta data.

## 0.0.8

- fix: Org-mode, strikethrough(del) syntax not work, #3
- fix: Make all URLs in MindMap opened to system browser to prevent stuck in Logseq, #4
- fix: Latex syntax not rendered at first time.
- fix: Shortcut `r` conflicts with Logseq `cmd`+`r`.
- feat: Improve parsing links, now pure links with text can be parsed correctly.
- feat: Finally, image partly supported, and will be convert to image link.

## 0.0.7

- feat: Support org format in a non-perfect way.
- feat: Make pure url clickable on Markmap.
- fix: Code block render issue.

## 0.0.6

- feat: Add a help popup modal, press `/` to trigger.
- feat: Add more shortcuts to change theme, move mindmap up, down, left, right.
- fix: Wrong "save as png" file name sometimes.

## 0.0.5

- feat: Add up to 16 themes.
- feat: Change auto dark mode to follow Logseq theme.
- Fix: corner toolbar color change with theme changing.

## 0.0.4

- Filter out front matter block.
- Show Logseq block tag.
- Add blur background effect.
- Support auto dark mode based on system theme.

## 0.0.3

- Fix some level and page switch issues.
- Add more shortcuts include traversing step by step, level by level, focusing in and out.

## 0.0.2

- Add shortcuts support.
- Add `save as png` toolbar.
- Optimize performance.

## 0.0.1

- Basic integration with `Markmap`.
