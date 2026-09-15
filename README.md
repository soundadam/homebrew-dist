# Homebrew Distribution Assets

Public, immutable distribution assets for [`soundadam/tap`](https://github.com/soundadam/homebrew-tap).

Source repositories are private. Homebrew Formulae and Casks depend only on this
public repository and on explicitly pinned public third-party resources. Each
Release records the private source repository, exact source ref/commit, asset
SHA-256 values, license boundary, and security state.

## Install

```bash
brew install soundadam/tap/codex-switch
brew install soundadam/tap/njuprobe
brew install soundadam/tap/teaway
brew install --cask soundadam/tap/codex-pulse
brew install --cask soundadam/tap/soundvpn
brew install --cask soundadam/tap/soundconnect
```

## Releases

| Package | Version | Release | License / security boundary |
| --- | --- | --- | --- |
| Codex Switch | 0.1.0 | [`codex-switch-v0.1.0`](https://github.com/soundadam/homebrew-dist/releases/tag/codex-switch-v0.1.0) | MIT source Formula |
| NJUProbe | 0.1.0 | [`njuprobe-v0.1.0`](https://github.com/soundadam/homebrew-dist/releases/tag/njuprobe-v0.1.0) | MIT application; pinned LGPL/Apache helper resources |
| Teaway | 0.2.2 | [`teaway-v0.2.2`](https://github.com/soundadam/homebrew-dist/releases/tag/teaway-v0.2.2) | MIT source Formula; power-state commands require attended use |
| Codex Pulse | 1.0.1 | [`codex-pulse-v1.0.1`](https://github.com/soundadam/homebrew-dist/releases/tag/codex-pulse-v1.0.1) | AGPLv3 binary plus exact corresponding source; ad-hoc signed, not notarized |
| SoundVPN | 0.2.0 preview | [`soundvpn-v0.2.0`](https://github.com/soundadam/homebrew-dist/releases/tag/soundvpn-v0.2.0) | AGPLv3 binary plus exact corresponding source; ad-hoc signed, not notarized |
| soundconnect | 1.1.0-alpha.1 preview | [`soundconnect-v1.1.0-alpha.1`](https://github.com/soundadam/homebrew-dist/releases/tag/soundconnect-v1.1.0-alpha.1) | Private-source binary only; ad-hoc signed, not notarized |

## Publication rules

- Releases are immutable. Corrections use a new project version and tag.
- Formula and Cask URLs must remain anonymously downloadable after source
  repositories become private.
- AGPL binary releases include exact corresponding-source archives, except
  the soundconnect preview, which publishes only the binary, checksum, and
  build manifest.
- Casks do not remove quarantine or modify Gatekeeper policy.
- This repository contains distribution metadata and assets only; it does not
  grant official university or vendor status to any package.
