# Changelog

## [1.2.0] - 2025-09-11

### Added

- Added ORCID support in title page.
- Added CI/CD workflows for compilation, linting, formatting, and releases.
- Added release workflow to automatically build and attach PDF on tag push.

### Changed

- Updated Declaration.tex to remove signature line per latest guidelines.
- Updated Preface.tex to include AI and digital assistance declarations per 2025 guidelines.
- Removed University of Melbourne logo from title page per thesis guidelines.
- Updated guidelines references to latest 2025 version.

### Fixed

- Fixed compilation issues and modernized LaTeX usage.

## [1.1.0] - 2024-07-25

### Added

- Added a `LICENSE` file with the MIT License.
- Added an example of a table with `siunitx` in `example/Chapters/Chapter1.tex`.
- Added an example of a figure with `tikz` in `example/Chapters/Chapter1.tex`.
- Added an example of a glossary with `glossaries` in `example/Preamble/Glossary.tex` and `example/Thesis.tex`.
- Added an example of an index with `makeidx` in `example/Thesis.tex`.
- Added University of Melbourne SVG logo to `example/Figures/unimelb_logo/`.

### Changed

- Updated `template/Thesis.cls` to include `siunitx`, `tikz`, `glossaries`, and `makeidx` packages.
- Updated `example/Chapters/Chapter1.tex` to demonstrate the new features.
- Updated `example/Thesis.tex` to include the glossary and index.
