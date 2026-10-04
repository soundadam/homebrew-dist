# Homebrew Distribution Assets

Public, immutable distribution assets for [`soundadam/tap`](https://github.com/soundadam/homebrew-tap).

Source repositories are private. Homebrew Formulae and Casks depend only on this
public repository and on explicitly pinned public third-party resources. Each
Release records the private source repository, exact source ref/commit, asset
SHA-256 values, license boundary, and security state.

## Install

```bash
brew install soundadam/tap/codex-switch
brew install --cask soundadam/tap/codex-pulse
brew install --cask soundadam/tap/mac-thermal-lab
```

## Releases

| Package | Version | Release | License / security boundary |
| --- | --- | --- | --- |
| Codex Switch | 0.1.0 | [`codex-switch-v0.1.0`](https://github.com/soundadam/homebrew-dist/releases/tag/codex-switch-v0.1.0) | MIT source Formula |
| Codex Pulse | 1.0.1 | [`codex-pulse-v1.0.1`](https://github.com/soundadam/homebrew-dist/releases/tag/codex-pulse-v1.0.1) | AGPLv3 binary plus exact corresponding source; ad-hoc signed, not notarized |
| Mac Thermal Lab | 0.2.0 preview | [`mac-thermal-lab-v0.2.0`](https://github.com/soundadam/homebrew-dist/releases/tag/mac-thermal-lab-v0.2.0) | AGPLv3 Apple Silicon binary plus exact corresponding source; ad-hoc signed, not notarized |

Packages whose source repository is public (nju-connect, pace, tea) ship from
their own GitHub Releases, not from here.

## Publication rules

- Releases are immutable. Corrections use a new project version and tag.
- Formula and Cask URLs must remain anonymously downloadable after source
  repositories become private.
- AGPL binary releases include exact corresponding-source archives.
- Casks do not remove quarantine or modify Gatekeeper policy.
- This repository contains distribution metadata and assets only; it does not
  grant official university or vendor status to any package.
