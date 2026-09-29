# Better Design

A design harness for AI coding agents. This plugin connects your agent to the Better Design MCP server, so the interfaces it builds use a real design system, follow design principles, and pass UI review checks.

## What your agent gets

- **A design system for your app.** Find one that fits your product, preview it, and install its components, or generate a custom one from a description or your own site.
- **Design principles.** Visual design, UX flows, forms, onboarding and interface copy, plus references for React Native, SwiftUI, Three.js and Shopify themes.
- **Review checks.** Accessibility, copy clarity and measured spacing for the screens your agent builds.
- **Icons you own.** Icon sets returned as React components, with no runtime CDN.

## What this repository holds

This repository holds the plugin files only: the manifests, the MCP server entry and two skills. The Better Design server and its design systems run at [better-design.com](https://better-design.com). Browse the catalog at [better-design.com/design-systems](https://better-design.com/design-systems).

| Skill | What it does |
| --- | --- |
| `build-with-better-design` | Chooses a design system with the user, installs it, and builds on it |
| `review-ui-with-better-design` | Reviews a screen for accessibility, visual design, copy clarity and spacing |

## Install

| Tool | How |
| --- | --- |
| Gemini CLI | `gemini extensions install https://github.com/better-designs/better-design-plugin` |
| Claude Code | `claude mcp add --transport http better-design https://better-design.com/api/mcp` |
| Any MCP client | Add the remote server `https://better-design.com/api/mcp` |

The first connection opens a Better Design sign-in. A free account works.

## Privacy

Better Design's [privacy policy](https://better-design.com/privacy) and [terms](https://better-design.com/terms) apply. Support: info@better-design.com.
