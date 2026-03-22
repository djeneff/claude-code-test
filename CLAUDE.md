# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

A collection of web projects built as standalone HTML files — no build system, no package manager, no dependencies. Each file is self-contained with inline CSS and JavaScript.

## Running the Project

Open any `.html` file directly in a browser:

```bash
open tictactoe.html
```

## Architecture

Each project is a single `.html` file containing:
- Inline `<style>` block for all CSS
- Inline `<script>` block for all JavaScript
- No external dependencies or CDN links

## Git & GitHub

- Repository: https://github.com/djeneff/claude-code-test
- Commit every meaningful change with a clear message and push to `origin/master`
- Use clean, descriptive commit messages (imperative mood, explain the "what" and "why")
