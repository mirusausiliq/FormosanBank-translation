# FormosanBank Translation

[![GitBook Documentation](https://img.shields.io/badge/docs-gitbook-blue)](https://ai4commsci.gitbook.io/formosanbank)
[![Main Repo](https://img.shields.io/badge/repo-FormosanBank/FormosanBank-lightgrey)](https://github.com/FormosanBank/FormosanBank)
[![Translation CI](https://img.shields.io/github/actions/workflow/status/FormosanBank/FormosanBank-Translation/translation-check.yml?branch=main)](https://github.com/FormosanBank/FormosanBank-Translation/actions)
[![License](https://img.shields.io/github/license/FormosanBank/FormosanBank-Translation)](https://github.com/FormosanBank/FormosanBank-Translation/blob/main/LICENSE)

> Central hub for all localization files and translation workflows across the FormosanBank ecosystem.

## Table of Contents

- [FormosanBank Translation](#formosanbank-translation)
  - [Table of Contents](#table-of-contents)
  - [Overview](#overview)
  - [Supported Languages](#supported-languages)
  - [Repository Layout](#repository-layout)
  - [File Naming Conventions](#file-naming-conventions)
  - [Translation Style Guide](#translation-style-guide)
  - [Contributing](#contributing)
  - [License](#license)
  - [Resources](#resources)

## Overview

This repository centralizes **markdown**‑based localization files for the FormosanBank platform, documentation, and user interface content. Each language directory contains translated `.md` documents—such as guides, tutorials, and UI copy—maintaining consistent structure and terminology across all supported locales.

## Supported Languages

| Code    | Language                    | Status       |
| ------- | --------------------------- | ------------ |
| `ami`   | Amis / Pangcah              | Adding       |
| `ckv`   | Kavalan (Kebalan)           | Adding       |
| ...     | ...                         | ...          |
| `en`    | English                     | Source       |
| `zh-TW` | Traditional Chinese         | Adding       |

*Source language (`en`) should always contain the complete set of keys.*

## Repository Layout

```text
FormosanBank-Translation/
├── ami/           # Amis / Pangcah translations
│   ├── 0 Welcome.md
│   └── ....
├── ckv/           # Kavalan (Kebalan)
│   ├── 0 Welcome.md
│   └── ....
├── en/            # English (source)
│   ├── 0 Welcome.md
│   ├── 1.1 Formosan Languages
│   └── ...
├── zh-TW/         # Traditional Chinese
│   ├── 0 Welcome.md
│   ├── 1.1 Formosan Languages
│   └── ...
├── CONTRIBUTING.md
├── LICENSE
└── README.md
```

## File Naming Conventions

- **Document name**: Identify the content or topic.
- **Language code**: Use BCP 47 tags (e.g., `ami`, `ckv`, `en`, `zh-TW`).
- **Extension**: Always `.md` for markdown files.

**Pattern**: `<doc-name>.<lang-code>.md`  
Example: `getting-started.zh-TW.md`.

Maintaining consistent file names and frontmatter keys (if used) ensures automated tooling can validate and assemble localized documentation.

## Translation Style Guide

For terminology, tone, and orthography standards, see the [FormosanBank Translation Style Guide](https://ai4commsci.gitbook.io/formosanbank/translation/style-guide).

## Contributing

We welcome community contributions! Please review [CONTRIBUTING.md](CONTRIBUTING.md) for:

- Issue reporting & labeling
- Branch naming conventions (`feat/translation-<lang>`)
- Commit message format (`feat(ami): add greeting texts`)
- Pull request process & review checklist

## License

Distributed under the MIT License. See [LICENSE](LICENSE) for details.

## Resources

- **Documentation**: https://ai4commsci.gitbook.io/formosanbank
- **Core Repo**: https://github.com/FormosanBank/FormosanBank
