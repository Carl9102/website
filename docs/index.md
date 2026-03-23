---
title: Introduction
description: What Pages CMS is, who it is for, and how it works.2026
---
## What Pages CMS is

[Pages CMS](https://pagescms.org) is an open-source CMS for static sites stored in GitHub repositories.

It edits files in your repository directly. There is no separate CMS database for content.

## Why it exists

Most static sites do not need a database-backed CMS. They already have:

- content in files,
- media in the repository,
- Git history,
- a deployment flow.

The missing piece is usually the editing experience.

Pages CMS gives teams a UI for editing content and media without asking every editor to learn Git.

## How it works

1. Add a `.pages.yml` file to the repository.
2. Define `content`, `media`, and any optional `components` or `settings`.
3. Sign in to Pages CMS.
4. Edit content in the UI.
5. Save changes back to GitHub.

## What Pages CMS does not do

Pages CMS does not replace your site generator, deployment platform, or repository workflow.

It only provides the editing layer on top of your existing Git-based project.

[Quick start {% lucide "arrow-right" %} Configuration overview {% lucide "arrow-right" %}](/docs/configuration)