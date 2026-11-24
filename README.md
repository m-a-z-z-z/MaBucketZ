# MaBucketZ

[![Tests](https://github.com/m-a-z-z-z/MaBucketZ/actions/workflows/ci.yml/badge.svg)](https://github.com/m-a-z-z-z/MaBucketZ/actions/workflows/ci.yml) [![Excavator](https://github.com/m-a-z-z-z/MaBucketZ/actions/workflows/excavator.yml/badge.svg)](https://github.com/m-a-z-z-z/MaBucketZ/actions/workflows/excavator.yml)

Personal [Scoop](https://scoop.sh) bucket for packages I did not find in the official Scoop buckets.

## Packages

| Manifest | Description |
|----------|-------------|
| [deja-vu](bucket/deja-vu.json) | Claude Code, Codex & Cursor memory — local MCP memory, session history search & coding agent handoff (from my [deja-vu](https://github.com/m-a-z-z-z/deja-vu) fork) |
| [pano-scrobbler](bucket/pano-scrobbler.json) | Feature rich scrobbler for Windows, Linux & Android. Supports Last.fm, ListenBrainz, Libre.fm & Pleroma |

## How do I install these manifests?

After manifests have been committed and pushed, run the following:

```pwsh
scoop bucket add mabucketz https://github.com/m-a-z-z-z/MaBucketZ
scoop install mabucketz/<manifestname>
```

<details>
<summary>If you get an error you might have to add this bucket first</summary>

```pwsh
scoop bucket add mabucketz
```
</details>

## How do I contribute new manifests?

To make a new manifest contribution, please read the [Contributing
Guide](https://github.com/ScoopInstaller/.github/blob/main/.github/CONTRIBUTING.md)
and [App Manifests](https://github.com/ScoopInstaller/Scoop/wiki/App-Manifests)
wiki page.
