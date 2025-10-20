# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a GitHub profile repository for Chris233 (a.k.a. Chris), containing a personalized README with profile information, tech stack badges, and GitHub statistics. The repository includes both English and Chinese versions of the README, and features a GitHub contribution snake animation.

## Repository Structure

- `README.md` - English version of the profile README
- `README_zh.md` - Chinese version of the profile README
- `commit.sh` - Simple script to commit all changes with message "..."
- `push.sh` - Simple script to push to origin main
- `.github/workflows/snake.yml` - GitHub Actions workflow to generate contribution snake animation

## Development Commands

- `./commit.sh` - Stages all changes and commits with default message "..."
- `./push.sh` - Pushes changes to the main branch
- Manual git commands can also be used for more granular control

## Tech Stack

The profile highlights expertise in:
- Rust (primary focus)
- C/C++
- Kotlin
- Python
- TypeScript
- Ubuntu/Linux
- Shell scripting

## Architecture Notes

- This is a static profile repository with no application code
- The contribution snake animation is generated automatically via GitHub Actions
- The workflow runs every 12 hours and on pushes to main branch
- Animation is generated using Platane/snk GitHub Action

## Special Features

- GitHub contribution grid snake animation (light/dark mode versions)
- GitHub stats and top languages display
- Typing SVG animation in header
- Multi-language README support (English/Chinese)