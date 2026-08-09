# zFlow Release Repository Boundary

This repository is for public release materials only.

## Purpose

It may contain:

- Product README content.
- Static website files.
- Demo video scripts, thumbnails, screenshots, and other public media assets.
- Installation, usage, privacy, and release documentation.
- Public package links and product messaging.

## Non-goals

It must not contain:

- zFlow source code from `/Users/bytedance/code/zflow`.
- Private development notes that expose implementation details not intended for users.
- Local secrets, signing credentials, npm tokens, or private environment files.
- Build artifacts that are not meant to be distributed through the chosen release channel.

## Source of Truth

The private source project at `/Users/bytedance/code/zflow` remains the source of truth for implementation, tests, packaging scripts, and internal development documentation.

This repository may reference product behavior from that project, but it should only publish user-facing facts: what zFlow does, how to install it, how to use it, and what privacy guarantees the product currently provides.

## Release Checklist

Before publishing updates from this repository:

- Confirm no source files were copied from the private project.
- Confirm all media files are intended for public release.
- Confirm README installation commands match the npm packages.
- Confirm website links and video links point to public, stable locations.
- Confirm privacy claims match current product behavior.
