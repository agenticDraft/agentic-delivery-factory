# agentic-delivery-factory

One Jira ticket, followed through one run of an agentic delivery pipeline, until it becomes a pull request.

The pipeline is fifteen steps. The orchestrator never reads code: each step reports back in a short fixed result, and the orchestrator reads only that.

This repo is the companion site to the [agentic-delivery plugins](https://github.com/agenticDraft/plugins). Each page walks through one part of the run:

1. The orchestrator that never reads code
2. The Jira part has no opinion
3. The Figma plugin, from design link to files
4. Conventions, serve and baseline: the project before the build
5. The Playwright plugin, from URL to observed page

**Read it: https://agenticdraft.github.io/agentic-delivery-factory/**

The pages are static HTML in [docs/](docs/), served by GitHub Pages from `main`.
