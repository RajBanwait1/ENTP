# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project status

A static site of class projects. Each project lives in its own folder as a single self-contained `index.html` (HTML, CSS, and JS in one file, no external dependencies). The root `index.html` is a landing page linking to each project.

## Commands

There is no build, test, or lint tooling. Open any `index.html` directly in a browser to run it.

## Architecture

- `index.html` — landing page. When adding a project, add a link to it here and to `README.md`.
- `GradeNeededCalculator/index.html` — grade-needed calculator.

## Deployment

Pushing to `main` auto-deploys to production via Vercel. Share the public URL `https://entp-chi.vercel.app`; the per-deployment `*.vercel.app` URLs require a Vercel login.
