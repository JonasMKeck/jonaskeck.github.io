
# Project instructions for Codex

## Project type
This repository is a simple static personal website hosted with GitHub Pages.
The site uses:
- plain HTML
- plain CSS
- no JavaScript
- no framework
- no build system
- no backend
Do not introduce React, Next.js, npm tooling, bundlers, templating systems, JavaScript, or external dependencies unless explicitly requested.

## General working style
Prefer small, targeted, inspectable edits.
Do not make broad refactors, redesigns, or structural reorganizations unless explicitly requested.
Preserve the existing visual design language unless the task explicitly asks for a visual change.
When editing, keep the change as narrow as possible:
- edit only the files required for the task
- preserve existing indentation and naming style where reasonable
- avoid unrelated cleanup
- do not rewrite whole files when a local edit is enough

## Safety and permissions
Do not edit, inspect, or modify `.git`.
Do not commit or push changes.
Do not create, delete, rename, or move files unless explicitly requested.
Do not install packages.
Do not use the network unless explicitly requested.
Do not run npm, Node, Python, build, test, install, shell, PowerShell, or Git commands unless explicitly requested.
If a command is needed, explain why first and keep it as narrow as possible.

## Website conventions
Use `style.css` for shared styling.
Reuse existing CSS classes where possible.
Use semantic HTML.
For PDF/download placeholders, use `<p class="download-placeholder">PDF forthcoming</p>`.
For real downloadable files, use the existing `download-link` pattern.
Do not use fake links such as `href="#"`.
Do not make placeholder text look like an active download link.

## Navigation
Navbar markup is duplicated across pages.
When changing navigation, update all relevant public pages consistently.
Do not delete hidden or temporarily unlinked pages unless explicitly requested.

## Output after edits
After making changes, summarize:
1. files changed
2. exact change made
3. files intentionally not changed
4. anything the user should verify in GitHub Desktop before committing

The user will review all diffs in GitHub Desktop and will commit/push manually.