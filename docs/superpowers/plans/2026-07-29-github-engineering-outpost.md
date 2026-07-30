# GitHub Engineering Outpost Implementation Plan

> **For agentic workers:** REQUIRED: Use superpowers:subagent-driven-development (if subagents available) or superpowers:executing-plans to implement this plan. Steps use checkbox (`- [ ]`) syntax for tracking.

**Goal:** Publish a concise ArchAstro organization profile and consistent community-health defaults.

**Architecture:** Use GitHub's special public `.github` repository for the visible organization profile and inherited community files. Keep repository-specific behavior in each repository and use GitHub metadata for discovery.

**Tech Stack:** GitHub organization profile, Markdown, GitHub REST/GraphQL APIs

---

## Chunk 1: Organization profile

- [ ] Publish `profile/README.md` with verified company, product, OSS, docs, and SDK links.
- [ ] Set the organization name, description, and company website.
- [ ] Verify every public link returns a successful response.

## Chunk 2: Community defaults

- [ ] Publish default conduct, contribution, security, and pull-request files.
- [ ] Confirm GitHub recognizes the organization profile repository.

## Chunk 3: Repository discovery

- [ ] Add descriptions, homepages, and targeted topics to flagship public repositories.
- [ ] Pin the flagship repositories when the available GitHub surface supports it.
- [ ] Record inaccessible account-level settings for manual completion.
