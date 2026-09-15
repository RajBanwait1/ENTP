# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project status

A grade-needed calculator: a single self-contained `GradeNeededCalculator/index.html` (HTML, CSS, and JS in one file, no external dependencies).

## Commands

There is no build, test, or lint tooling. Open `GradeNeededCalculator/index.html` directly in a browser to run it.

## Architecture

There is no root `index.html`. `vercel.json` rewrites `/` to `/GradeNeededCalculator/index.html`, so the app is served at the site root while its source stays in its folder. Vercel serves real files before applying rewrites, so adding a root `index.html` would replace the app at `/`.

## Deployment

Pushing to `main` auto-deploys to production via Vercel. Share the public URL `https://entp-chi.vercel.app`; the per-deployment `*.vercel.app` URLs require a Vercel login.
