# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a Jekyll-based website for the Asian-Pacific Condensed Matter Physics (AP-CMP) seminars. It's a simple static site hosted on GitHub Pages that provides information about the seminar series, upcoming speakers, and participation guidelines.

## Site Structure

- `_config.yml`: Jekyll configuration with site title and theme (jekyll-theme-slate)
- `index.md`: Main page with seminar information, mailing list details, organizers, and current seminar schedule
- `schedule.md`: Working document with speaker schedule table and availability planning
- `README.md`: Simple redirect pointing to the schedule file

## Key Information

- **Main website**: https://asian-pacific-cmp-seminars.github.io/
- **Working document**: https://docs.google.com/document/d/1WtgDLoIaoAS32dmFT3qDyThqxH-MufJYObCSJ1wFTvs/edit?tab=t.0
- **Admin contact**: mapcmpseminar_admin@googlegroups.com

## Content Management

The site primarily manages two types of content:
1. **Static information** (organizers, guidelines, contact) in `index.md`
2. **Schedule information** in both `index.md` (public-facing) and `schedule.md` (planning document)

When updating seminar information, ensure consistency between the detailed seminar entries in `index.md` and the schedule table in `schedule.md`.

## Deployment

The site uses GitHub Pages with Jekyll, so changes to markdown files are automatically deployed when pushed to the main branch.