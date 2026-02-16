# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

A standalone shopping list web app built as a single `index.html` file. No build tools, frameworks, or dependencies — pure HTML/CSS/JavaScript that runs directly in the browser.

## Development

Open `index.html` in a browser to run the app. No build step or server required.

## Architecture

- **Single-file app**: All markup, styles, and logic live in `index.html`
- **Persistence**: Uses `localStorage` (key: `shopping-list`) to store items as JSON
- **Data model**: Array of `{ name: string, done: boolean }` objects
- **UI language**: Korean (ko)
