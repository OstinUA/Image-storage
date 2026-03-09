# Image Storage

> Asset-first repository for hosting, versioning, and serving reusable image resources.

[![Repo Size](https://img.shields.io/github/repo-size/OstinUA/Image-storage?style=for-the-badge)](https://github.com/OstinUA/Image-storage)
[![Last Commit](https://img.shields.io/github/last-commit/OstinUA/Image-storage?style=for-the-badge)](https://github.com/OstinUA/Image-storage/commits/main)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)](LICENSE)

> [!NOTE]
> Project structure below is auto-generated on every push via [update-readme.yml](.github/workflows/update-readme.yml)

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
- License clarity via an included `MIT` license file.

> [!TIP]
> Keep binary filenames stable once published to avoid breaking external links.

## Technology Stack

- **Core format:** static binary assets (`.png`) and lightweight docs (`.md`).
- **Delivery model:** GitHub repository + `raw.githubusercontent.com` direct asset URLs.
- **Markup:** `HTML` (for in-repo preview/demo via `index.html`) and `Markdown` for docs.
- **Version control:** `Git` + GitHub workflow.

## Technical Block

### Project Structure

<!-- STRUCTURE_START -->
<!-- STRUCTURE_END -->

### Key Design Decisions

1. **Flat and explicit storage layout**
   Assets are grouped in simple directories to keep paths human-readable and predictable.

2. **No runtime dependency surface**
   The repository intentionally avoids backend services, build steps, or package managers.

3. **Raw-link friendly strategy**
   Files are stored in a way that supports direct consumption through GitHub raw links for quick integrations.

4. **Documentation-first maintainability**
   The README defines structure, usage expectations, and operational guardrails.

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

This project is distributed under the `MIT` license. See [`LICENSE`](LICENSE) for details.
