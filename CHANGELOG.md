# Changelog

## 0.3.0 · 2026-11-18

- Sessions for AI programs: while Claude Code or Codex runs, `⌥S` lists the conversations it saved for the folder. Resume one in the same pane, a new pane or a new tab, start a new one, archive one or move it to the Trash.
- Git panel (`⌘G`): staged, changed and untracked files with their diffs, stage, unstage, discard, commit, stash, branches, fetch, pull and push, and the history drawn as lanes with forks and merges.
- `⌘V` with an image on the clipboard attaches it in Claude Code and Codex; in the shell it pastes the path of a saved copy.
- Path suggestions: `⇥` and `↩` take the highlighted item and close the list, `→` opens a folder, `←` goes back up.
- The prompt editor wraps long lines and grows to the size of the pane with `⇧⌘E`.
- Right panels resize by dragging their edge.
- Fixed a crash when typing accents with dead keys (´ ¨). Problems are now written to `~/Library/Logs/Cmdlyne/cmdlyne.log`.

## 0.2.0 · 2026-11-18

- Pinned folders in each space: click one to open a new tab there, `⌥⌘P` pins the current folder.
- Saved prompts for AI programs: a bar appears while Claude Code, Codex or another AI program runs, and `⌥P` types a prompt into it without sending it.
- Notifications and dots when a command finishes or fails out of view, or when an AI program waits for you.
- A close button on each pane of a split.
- Double-click the top bar to fill the screen without going full screen.

## 0.1.1 · 2026-11-18

- `Esc` closes the suggestions list.
- A renamed space keeps its name when you switch away and back.

## 0.1.0 · 2026-11-18

- First release: command blocks, an input that edits like an editor, spaces and tabs by recent use, split panes, the library with workflows and notebooks, a team folder, themes, and AI through the Claude Code or Codex CLI you already use.
