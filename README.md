# Prehistoric Tribes Web runtime assets

This public repository contains only the runtime assets required by the clean-room Godot Web prototype. The playable page is served separately from https://twsoft.ai/game/.

- Source project: `tw-soft/prehistoric-tribes`
- Production baseline: `v1.0.0` → `1963533f0f03aad12c1ca284e31d0e96a818b7d9`
- Animation version: merge `c49251009a8d1e5ce2809c4d9eac2b69c8d56a01`
- Godot: `4.7.2.stable.official.ed1daf0bf`
- Export: single-threaded Web, no GDExtension
- Directories: `web-v1/` is the production baseline; `web-v2/` is the animated version

Do not add source Java, reverse-engineering outputs, credentials, or editor/plugin files here. The large WebAssembly files are kept outside Cloudflare Pages because Pages has a 25 MiB per-file limit.
