# 1. Project Tech Stack

Date: 2020-09-20

## Status

Accepted

## Context

This project has 2 goals: build web scrapers to collect tennis data & display this data via a modernized, aesthetic website.

The statistics will be displayed in a static fashion. The website will display the latest statistics from the time the web scraping script(s) were run manually.

## Decision

### Tools
- Web Scraping - Python 3.8
- Statistics Display SPA - Angular CLI 10.1
- Deployment - GitHub Pages

## Consequences

Angular as tool choice may disallow the use of some native JS libraries. The developers are confident in the existence of alternative TS packages, as well as their ability to implement any required functionality in TypeScript.

Python is used regularly for web scraping and the team foresees no significant issues.