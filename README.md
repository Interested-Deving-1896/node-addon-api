[update-readmes]   Mode: rewrite — migrating to template structure...
# node-addon-api

[![Built with Ona](https://ona.com/build-with-ona.svg)](https://app.ona.com/#https://github.com/Interested-Deving-1896/node-addon-api)

<!-- AI:start:what-it-does -->
This project provides a C++ wrapper for Node-API, enabling developers to create native Node.js addons using C++ with simplified syntax and improved usability. It addresses the complexity of directly interacting with Node-API by offering abstractions that streamline development. It is used by developers building high-performance native modules for Node.js applications.
<!-- AI:end:what-it-does -->

## Architecture

<!-- AI:start:architecture -->
The project provides a C++ wrapper for Node-API, enabling the development of Node.js native addons. It abstracts the Node-API C interface, simplifying addon creation while maintaining compatibility across Node.js versions.

Key components:
- **`napi.h` and `napi-inl.h`**: Core headers defining the C++ API.
- **`node_addon_api.gyp`**: Build configuration for addons using this module.
- **`test/`**: Unit tests for validating functionality.
- **`benchmark/`**: Performance benchmarks for the API.
- **`.github/workflows/`**: CI workflows for testing, linting, and releasing.

Directory structure:
```plaintext
.
├── benchmark/            # Performance benchmarks
├── doc/                  # Documentation files
├── test/                 # Unit tests
├── tools/                # Utility scripts
├── .github/workflows/    # CI/CD workflows
├── napi.h                # Core C++ API header
├── napi-inl.h            # Inline implementations for the API
├── node_addon_api.gyp    # Build configuration for addons
├── package.json          # Project metadata
└── README.md             # Project overview
```
<!-- AI:end:architecture -->

## Install

<!-- Add installation instructions here. This section is yours — the AI will not modify it. -->

```bash
git clone https://github.com/Interested-Deving-1896/node-addon-api.git
cd node-addon-api
```

## Usage

<!-- Add usage examples here. This section is yours — the AI will not modify it. -->

## Configuration

<!-- Document configuration options here. This section is yours — the AI will not modify it. -->

## CI

<!-- AI:start:ci -->
The project uses GitHub Actions for continuous integration and other automated workflows. Below is a summary of the workflows:

- **ci.yml**: Runs tests and builds on Linux and macOS for supported Node.js versions. No secrets required.
- **ci-win.yml**: Runs tests and builds on Windows for supported Node.js versions. No secrets required.
- **codeql.yml**: Performs static code analysis using CodeQL. No secrets required.
- **coverage-linux.yml**: Generates code coverage reports on Linux. No secrets required.
- **dependency-review.yml**: Checks for vulnerable dependencies in pull requests. No secrets required.
- **linter.yml**: Runs linting checks using ESLint. No secrets required.
- **node-api-headers.yml**: Downloads and caches Node-API headers for use in builds. No secrets required.
- **release-please.yml**: Automates release creation and changelog updates. Requires `GITHUB_TOKEN` (provided by default).
- **scorecards.yml**: Runs OpenSSF Scorecards to assess repository security. No secrets required.
- **stale.yml**: Marks inactive issues and pull requests as stale. No secrets required.
<!-- AI:end:ci -->

## Mirror chain

<!-- AI:start:mirror-chain -->
This repo is maintained in [`Interested-Deving-1896/node-addon-api`](https://github.com/Interested-Deving-1896/node-addon-api) and mirrored through:

```
Interested-Deving-1896/node-addon-api  ──►  OpenOS-Project-OSP/node-addon-api  ──►  OpenOS-Project-Ecosystem-OOC/node-addon-api
```

Changes flow downstream automatically via the hourly mirror chain in
[`fork-sync-all`](https://github.com/Interested-Deving-1896/fork-sync-all).
Direct commits to OSP or OOC are detected and opened as PRs back to `Interested-Deving-1896`.
<!-- AI:end:mirror-chain -->

## Contributors

<!-- AI:start:contributors -->
[@dependabot[bot]](https://github.com/dependabot[bot]) (132 commits)  
[@KevinEady](https://github.com/KevinEady) (85 commits)  
[@NickNaso](https://github.com/NickNaso) (76 commits)  
[@legendecas](https://github.com/legendecas) (62 commits)  
[@mhdawson](https://github.com/mhdawson) (55 commits)  
[@JckXia](https://github.com/JckXia) (44 commits)  
[@jasongin](https://github.com/jasongin) (40 commits)  
[@addaleax](https://github.com/addaleax) (23 commits)  
[@romandev](https://github.com/romandev) (22 commits)  
[@tniessen](https://github.com/tniessen) (20 commits)  
[@gabrielschulhof](https://github.com/gabrielschulhof) (15 commits)  
[@RaisinTen](https://github.com/RaisinTen) (13 commits)  
[@jschlight](https://github.com/jschlight) (9 commits)  
[@github-actions[bot]](https://github.com/github-actions[bot]) (8 commits)  
[@rolftimmermans](https://github.com/rolftimmermans) (8 commits)  
[@kfarnung](https://github.com/kfarnung) (7 commits)  
[@digitalinfinity](https://github.com/digitalinfinity) (6 commits)  
[@yjaeseok](https://github.com/yjaeseok) (5 commits)  
[@vmoroz](https://github.com/vmoroz) (5 commits)  
[@lovell](https://github.com/lovell) (5 commits)  
[@nadongguri](https://github.com/nadongguri) (4 commits)  
[@DaAitch](https://github.com/DaAitch) (4 commits)  
[@JoseExposito](https://github.com/JoseExposito) (3 commits)  
[@devsnek](https://github.com/devsnek) (3 commits)  
[@davedoesdev](https://github.com/davedoesdev) (3 commits)  
[@rivertam](https://github.com/rivertam) (3 commits)  
[@rubiagatra](https://github.com/rubiagatra) (2 commits)  
[@seishun](https://github.com/seishun) (2 commits)  
[@mildsunrise](https://github.com/mildsunrise) (2 commits)  
[@strager](https://github.com/strager) (2 commits)  

This repository may be a mirror. Please check the [upstream source](https://github.com/nodejs/node-addon-api) for additional contributions.
<!-- AI:end:contributors -->

## Origins

<!-- AI:start:origins -->
_Original project — no upstream fork._
<!-- AI:end:origins -->

## Resources

<!-- AI:start:resources -->
_No additional resource files found._
<!-- AI:end:resources -->

## License

<!-- AI:start:license -->
[MIT](https://github.com/Interested-Deving-1896/node-addon-api/blob/main/LICENSE.md) © 2026 [Interested-Deving-1896](https://github.com/Interested-Deving-1896)
<!-- AI:end:license -->
