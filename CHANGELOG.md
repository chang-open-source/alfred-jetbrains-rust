# Changelog

## [0.5.0](https://github.com/chang-open-source/alfred-jetbrains-rust/compare/v0.4.0...v0.5.0) (2026-11-25)


### Bug Fixes

* handle search text and project discovery edge cases ([bba26bf](https://github.com/chang-open-source/alfred-jetbrains-rust/commit/bba26bf151e6354847b2b69d7ed04b2fc3d74433))
* preserve launcher fallback when opening IDE apps ([45f6dd5](https://github.com/chang-open-source/alfred-jetbrains-rust/commit/45f6dd51f66dd1dfc8ad1a0d2637967d7247deaf))
* preserve project state and correct IDE, worktree and workflow discovery ([a2a4b8e](https://github.com/chang-open-source/alfred-jetbrains-rust/commit/a2a4b8e4de4474650c9bec79f6e8df4c98b10bbf))
* reuse running JetBrains IDEs when opening projects ([bff9395](https://github.com/chang-open-source/alfred-jetbrains-rust/commit/bff9395494755eec318200ee28808b006804d861))

## [0.4.0](https://github.com/chang-open-source/alfred-jetbrains-rust/compare/v0.3.1...v0.4.0) (2026-11-03)


### Bug Fixes

* report release checks for protected main branch ([603a37c](https://github.com/chang-open-source/alfred-jetbrains-rust/commit/603a37c13a20001eb718d6e7e11d3d60996aff1e))
* update repository paths after organization transfer ([b47939e](https://github.com/chang-open-source/alfred-jetbrains-rust/commit/b47939e7f724782985d6d1d91dc1c98ba5f67675))

## [0.3.1](https://github.com/chang-open-source/alfred-jetbrains-rust/compare/v0.3.0...v0.3.1) (2026-11-03)


### Features

* support workflow updates directly from Alfred ([bad6eaf](https://github.com/chang-open-source/alfred-jetbrains-rust/commit/bad6eaf922799dc33d1130c7a71d36c7973632b5))

## [0.3.0](https://github.com/chang-open-source/alfred-jetbrains-rust/compare/v0.2.0...v0.3.0) (2026-11-03)


### Features

* improve workflow layout and document features ([2fab094](https://github.com/chang-open-source/alfred-jetbrains-rust/commit/2fab094765819dd30b306a06c94ccbea30b5cb7e))
* support workflow upgrades and add jb update ([2285417](https://github.com/chang-open-source/alfred-jetbrains-rust/commit/22854171cddcdd6356437e254affb36bf3e3f4e7))

## [0.2.0] - 2026-11-02

- Add a universal `.alfredworkflow` package and a SHA256-verified one-command installer.
- Add workflow export and automated release publishing on version tags.

## [0.1.0] - 2026-11-02

- Initial Rust workflow with project search, pins, Git worktrees, and IDE detection.
- Add Apple Silicon/Intel CI, a new icon, and the MIT license.

[0.1.0]: https://github.com/chang-open-source/alfred-jetbrains-rust/releases/tag/v0.1.0
[0.2.0]: https://github.com/chang-open-source/alfred-jetbrains-rust/releases/tag/v0.2.0
