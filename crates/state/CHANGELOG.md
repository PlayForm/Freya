# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [0.2.2](https://github.com/PlayForm/Freya/compare/freya-node-state-v0.2.1...freya-node-state-v0.2.2) - 2024-09-04

### Added
- Support percentage of auto in layout ([#784](https://github.com/PlayForm/Freya/pull/784))
- Add missing gradient functions ([#776](https://github.com/PlayForm/Freya/pull/776))
- Panic when an attribute has a wrongly-formatted value, but only in debug builds to easily spot bugs ([#759](https://github.com/PlayForm/Freya/pull/759))
- Support `space-between`/`space-around`/`space-evenly` alignments ([#758](https://github.com/PlayForm/Freya/pull/758))
- `highlight_mode` attribute ([#704](https://github.com/PlayForm/Freya/pull/704))
- Expose scale factor ([#607](https://github.com/PlayForm/Freya/pull/607))
- Reactive scale factor ([#606](https://github.com/PlayForm/Freya/pull/606))
- Revamp internal text selection ([#647](https://github.com/PlayForm/Freya/pull/647))

### Fixed
- Support `none` for background colors

### Other
- Add opengl_rtt example. ([#813](https://github.com/PlayForm/Freya/pull/813))
- Allow `none` for non-text colors attributes
- Compile error for attribute parsing in --release
- Rename node states to follow an unified naming ([#713](https://github.com/PlayForm/Freya/pull/713))
- Move rendering to `freya-core` ([#712](https://github.com/PlayForm/Freya/pull/712))
- Rust 1.79 ([#710](https://github.com/PlayForm/Freya/pull/710))
- `rustfmt.toml` ([#689](https://github.com/PlayForm/Freya/pull/689))
- Run clippy in tests and examples
- release-plz.toml
- Only release crates under /crates