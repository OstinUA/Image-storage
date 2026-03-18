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
```text
.
├── Factorio/
│   └── Gear-silhouette-of-the-Factorio-logo.png
├── adwmg/
│   └── pidpus-2.png
├── readme/
│   └── readme-SVG-Banned-words_contributing.png
│   └── readme-SVG-Banned-words_readme.png
│   └── readme-SVG-Banned-words_security.png
│   └── readme-SVG-Banned-words_сodeofсonduct.png
│   └── OstinUA_Looping_Donut-(1).gif
│   └── OstinUA_github_readme_v1.gif
│   └── OstinUA_github_readme_v1Donut.gif
│   └── OstinUA_github_readme_v1Donut.svg
│   └── OstinUA_github_readme_v2.gif
│   └── OstinUA_github_readme_v3.gif
│   └── OstinUA_github_readme_v4.gif
│   └── OstinUA_github_readme_v7.gif
├── index.html
├── LICENSE
└── README.md
```

#### 📁 `Factorio`

| Preview | File | Raw URL |
|---------|------|---------|
| <img src="https://raw.githubusercontent.com/OstinUA/Image-storage/main/Factorio/Gear-silhouette-of-the-Factorio-logo.png" height="32"> | `Gear-silhouette-of-the-Factorio-logo.png` | [link](https://raw.githubusercontent.com/OstinUA/Image-storage/main/Factorio/Gear-silhouette-of-the-Factorio-logo.png) |

#### 📁 `adwmg`

| Preview | File | Raw URL |
|---------|------|---------|
| <img src="https://raw.githubusercontent.com/OstinUA/Image-storage/main/adwmg/pidpus-2.png" height="32"> | `pidpus-2.png` | [link](https://raw.githubusercontent.com/OstinUA/Image-storage/main/adwmg/pidpus-2.png) |

#### 📁 `readme`

| Preview | File | Raw URL |
|---------|------|---------|
| <img src="https://raw.githubusercontent.com/OstinUA/Image-storage/main/readme/OstinUA_Looping_Donut-(1).gif" height="32"> | `OstinUA_Looping_Donut-(1).gif` | [link](https://raw.githubusercontent.com/OstinUA/Image-storage/main/readme/OstinUA_Looping_Donut-(1).gif) |
| <img src="https://raw.githubusercontent.com/OstinUA/Image-storage/main/readme/OstinUA_github_readme_v1.gif" height="32"> | `OstinUA_github_readme_v1.gif` | [link](https://raw.githubusercontent.com/OstinUA/Image-storage/main/readme/OstinUA_github_readme_v1.gif) |
| <img src="https://raw.githubusercontent.com/OstinUA/Image-storage/main/readme/OstinUA_github_readme_v1Donut.gif" height="32"> | `OstinUA_github_readme_v1Donut.gif` | [link](https://raw.githubusercontent.com/OstinUA/Image-storage/main/readme/OstinUA_github_readme_v1Donut.gif) |
| <img src="https://raw.githubusercontent.com/OstinUA/Image-storage/main/readme/OstinUA_github_readme_v1Donut.svg" height="32"> | `OstinUA_github_readme_v1Donut.svg` | [link](https://raw.githubusercontent.com/OstinUA/Image-storage/main/readme/OstinUA_github_readme_v1Donut.svg) |
| <img src="https://raw.githubusercontent.com/OstinUA/Image-storage/main/readme/OstinUA_github_readme_v2.gif" height="32"> | `OstinUA_github_readme_v2.gif` | [link](https://raw.githubusercontent.com/OstinUA/Image-storage/main/readme/OstinUA_github_readme_v2.gif) |
| <img src="https://raw.githubusercontent.com/OstinUA/Image-storage/main/readme/OstinUA_github_readme_v3.gif" height="32"> | `OstinUA_github_readme_v3.gif` | [link](https://raw.githubusercontent.com/OstinUA/Image-storage/main/readme/OstinUA_github_readme_v3.gif) |
| <img src="https://raw.githubusercontent.com/OstinUA/Image-storage/main/readme/OstinUA_github_readme_v4.gif" height="32"> | `OstinUA_github_readme_v4.gif` | [link](https://raw.githubusercontent.com/OstinUA/Image-storage/main/readme/OstinUA_github_readme_v4.gif) |
| <img src="https://raw.githubusercontent.com/OstinUA/Image-storage/main/readme/OstinUA_github_readme_v7.gif" height="32"> | `OstinUA_github_readme_v7.gif` | [link](https://raw.githubusercontent.com/OstinUA/Image-storage/main/readme/OstinUA_github_readme_v7.gif) |

#### 📁 `readme/Banned-words`

| Preview | File | Raw URL |
|---------|------|---------|
| <img src="https://raw.githubusercontent.com/OstinUA/Image-storage/main/readme/Banned-words/readme-SVG-Banned-words_contributing.png" height="32"> | `readme-SVG-Banned-words_contributing.png` | [link](https://raw.githubusercontent.com/OstinUA/Image-storage/main/readme/Banned-words/readme-SVG-Banned-words_contributing.png) |
| <img src="https://raw.githubusercontent.com/OstinUA/Image-storage/main/readme/Banned-words/readme-SVG-Banned-words_readme.png" height="32"> | `readme-SVG-Banned-words_readme.png` | [link](https://raw.githubusercontent.com/OstinUA/Image-storage/main/readme/Banned-words/readme-SVG-Banned-words_readme.png) |
| <img src="https://raw.githubusercontent.com/OstinUA/Image-storage/main/readme/Banned-words/readme-SVG-Banned-words_security.png" height="32"> | `readme-SVG-Banned-words_security.png` | [link](https://raw.githubusercontent.com/OstinUA/Image-storage/main/readme/Banned-words/readme-SVG-Banned-words_security.png) |
| <img src="https://raw.githubusercontent.com/OstinUA/Image-storage/main/readme/Banned-words/readme-SVG-Banned-words_сodeofсonduct.png" height="32"> | `readme-SVG-Banned-words_сodeofсonduct.png` | [link](https://raw.githubusercontent.com/OstinUA/Image-storage/main/readme/Banned-words/readme-SVG-Banned-words_сodeofсonduct.png) |

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
