# Image Storage

> Asset-first repository for hosting, versioning, and serving reusable image resources.

[![Repo Size](https://img.shields.io/github/repo-size/OstinUA/Image-storage?style=for-the-badge)](https://github.com/OstinUA/Image-storage)
[![Last Commit](https://img.shields.io/github/last-commit/OstinUA/Image-storage?style=for-the-badge)](https://github.com/OstinUA/Image-storage/commits/main)
[![License: GPL-3.0](https://img.shields.io/badge/License-GPL--3.0-blue?style=for-the-badge)](LICENSE)
[![Coverage](https://img.shields.io/badge/coverage-n%2Fa-lightgrey?style=for-the-badge)](#)

> [!NOTE]
> This repo was originally a minimal image drop (the old README contained only a direct image link). It now documents the project as a maintainable asset storage workspace.

## Table of Contents

- [Features](#features)
- [Technology Stack](#technology-stack)
- [Technical Block](#technical-block)
  - [Project Structure](#project-structure)
  - [Key Design Decisions](#key-design-decisions)
- [Usage](#usage)
- [License](#license)

## Features

- Centralized storage for static image assets used across projects.
- Git-based versioning for deterministic asset history and rollback.
- Lightweight structure with predictable paths for direct raw-content linking.
- Ready-to-use files for web pages and external embedding.
- License clarity via an included `GPL-3.0` license file.

> [!TIP]
> Keep binary filenames stable once published to avoid breaking external links.

## Technology Stack

- **Core format:** static binary assets (`.png`) and lightweight docs (`.md`).
- **Delivery model:** GitHub repository + `raw.githubusercontent.com` direct asset URLs.
- **Markup:** `HTML` (for in-repo preview/demo via `index.html`) and `Markdown` for docs.
- **Version control:** `Git` + GitHub workflow.

## Technical Block

### Project Structure

```text
.
├── Factorio/
│   └── Gear-silhouette-of-the-Factorio-logo.png
├── adwmg/
│   └── pidpus-2.png
├── index.html
├── LICENSE
└── README.md
```

### Key Design Decisions

1. **Flat and explicit storage layout**  
   Assets are grouped in simple directories to keep paths human-readable and predictable.

2. **No runtime dependency surface**  
   The repository intentionally avoids backend services, build steps, or package managers.

3. **Raw-link friendly strategy**  
   Files are stored in a way that supports direct consumption through GitHub raw links for quick integrations.

4. **Documentation-first maintainability**  
   The README now defines structure, usage expectations, and operational guardrails.

> [!IMPORTANT]
> If this repository is used as a public CDN-like source, treat path changes as breaking changes.

> [!WARNING]
> Do not rewrite image history aggressively in shared branches (`git push --force`) if downstream systems depend on commit-pinned asset URLs.

## Usage

Use a direct raw URL pattern for any stored image:

```text
https://raw.githubusercontent.com/<owner>/<repo>/<branch>/<path-to-image>
```

Example from this repo:

```text
https://raw.githubusercontent.com/OstinUA/Image-storage/main/adwmg/pidpus-2.png
```

> [!CAUTION]
> Prefer branch protection and reviewed PRs before replacing existing public assets.

## License

This project is distributed under the `GPL-3.0` license. See [`LICENSE`](LICENSE) for details.
