> **⚠️ This repository is archived and no longer maintained.**
> It is read-only and will not receive further updates or contributions.

# Awesome oCIS

<!-- OSPO-managed README | Generated: 2026-04-16 | v2 -->

[![License](https://img.shields.io/badge/License-Apache--2.0-blue.svg)](LICENSE) [![ownCloud OSPO](https://img.shields.io/badge/OSPO-ownCloud-blue)](https://kiteworks.com/opensource) [![Docker Hub](https://img.shields.io/docker/pulls/owncloud)](https://hub.docker.com/r/owncloud/ocis)

An opinionated list of awesome [ownCloud Infinite Scale (oCIS)](https://github.com/owncloud/ocis) apps, extensions, services, and other resources. This curated collection includes viewers and editors (3D models, DICOM, draw.io, EPub, PDF, and more), file actions (cast, unzip), sidebar panels, progress bars, and authentication extensions built by the oCIS community.

## Part of oCIS

This repository is a community resource directory for the [ownCloud Infinite Scale (oCIS)](https://github.com/owncloud/ocis) ecosystem. It showcases third-party and official apps and extensions that extend oCIS functionality. For developer documentation on building oCIS apps, see [owncloud.dev](https://owncloud.dev).

This component is part of the [oCIS Docker image](https://hub.docker.com/r/owncloud/ocis).

## Getting Started

Browse the curated list below or in the main README. To install any of the listed apps and extensions, follow the steps in the [oCIS developer documentation](https://owncloud.dev/services/web/#web-apps). App installation as described in the developer documentation is available in oCIS v6.0.0 or later.

To build your own apps, start with the [app boilerplate](https://github.com/owncloud/web-app-skeleton).

## Documentation

- [oCIS developer documentation](https://owncloud.dev)
- [Web app installation guide](https://owncloud.dev/services/web/#web-apps)
- [oCIS documentation](https://doc.owncloud.com)

## Reference

Community-built apps and extensions for oCIS, organized by category.

### Viewers & Editors

* [3D Model Viewer](https://github.com/saw-jan/web-app-3dmodel-viewer) - View 3D models based on three.js
* [Arcade](https://github.com/fschade/ocis-arcade) - Play NES games based on nes-vue
* [Dicom Viewer](https://github.com/owncloud/web-app-dicom-viewer) - Preview medical images based on Cornerstone3D
* [Draw.io](https://github.com/owncloud/web-extensions/tree/main/packages/web-app-draw-io) - View and edit draw.io diagrams
* [EPub Reader](https://github.com/owncloud/web/tree/master/packages/web-app-epub-reader) - Read eBooks in .epub format
* [GPX Viewer](https://github.com/dschmidt/web-app-gpx-viewer) - Render GPX files in a map view
* [PDF Viewer](https://github.com/owncloud/web/tree/master/packages/web-app-pdf-viewer) - Read PDFs using native browser rendering
* [Presentation Viewer](http://github.com/JankariTech/web-app-presentation-viewer) - Render markdown presentations with reveal.js
* [Preview](https://github.com/owncloud/web/tree/master/packages/web-app-preview) - View images, watch videos and listen to audio
* [Text Editor](https://github.com/owncloud/web/tree/master/packages/web-app-text-editor) - Edit markdown and plain text files
* [Excalidraw](https://github.com/LukasHirt/oc-excalidraw/) - Sketch diagrams using Excalidraw whiteboard

### File Actions

* [Cast](https://github.com/owncloud/web-extensions/tree/main/packages/web-app-cast) - Send images and videos to Chrome Cast
* [Unzip](https://github.com/owncloud/web-extensions/tree/main/packages/web-app-unzip) - Unzip .zip files into the current folder

### Authentication

* [App Tokens](https://github.com/mschlachter/ocis-app-tokens) - Manage app tokens using the Auth App Service

## Community & Support

**[Star](https://github.com/owncloud/awesome-ocis)** this repo and **Watch** for release notifications!

- [ownCloud Website](https://owncloud.com)
- [Community Discussions](https://github.com/orgs/owncloud/discussions)
- [Matrix Chat](https://app.element.io/#/room/#owncloud:matrix.org)
- [Documentation](https://doc.owncloud.com)
- [Enterprise Support](https://owncloud.com/contact-us/)
- [OSPO Home](https://kiteworks.com/opensource)

## Contributing

We welcome contributions! Please read the [Contributing Guidelines](CONTRIBUTING.md)
and our [Code of Conduct](CODE_OF_CONDUCT.md) before getting started.

### Workflow

- **Rebase Early, Rebase Often!** We use a rebase workflow. Always rebase on the target branch before submitting a PR.
- **Dependabot**: Automated dependency updates are managed via Dependabot. Review and merge dependency PRs promptly.
- **Signed Commits**: All commits **must** be PGP/GPG signed. See [GitHub's signing guide](https://docs.github.com/en/authentication/managing-commit-signature-verification).
- **DCO Sign-off**: Every commit must carry a `Signed-off-by` line:
  ```
  git commit -s -S -m "your commit message"
  ```
- **GitHub Actions Policy**: Workflows may only use actions that are (a) owned by `owncloud`, (b) created by GitHub (`actions/*`), or (c) verified in the GitHub Marketplace.

## Security

**Do not open a public GitHub issue for security vulnerabilities.**

Report vulnerabilities at **<https://security.owncloud.com>** -- see [SECURITY.md](SECURITY.md).

Bug bounty: [YesWeHack ownCloud Program](https://yeswehack.com/programs/owncloud-bug-bounty-program)

## License

This project is licensed under the [Apache-2.0](LICENSE).

## About the ownCloud OSPO

The [Kiteworks Open Source Program Office](https://kiteworks.com/opensource), operating under
the [ownCloud](https://owncloud.com) brand, launched on May 5, 2026, to steward the open source
ecosystem around ownCloud's products. The OSPO ensures transparent governance, license compliance,
community health, and sustainable collaboration between the open source community and
[Kiteworks](https://www.kiteworks.com), which acquired ownCloud in 2023.

- **OSPO Home**: <https://kiteworks.com/opensource>
- **GitHub**: <https://github.com/owncloud>
- **ownCloud**: <https://owncloud.com>

For questions about the OSPO or licensing, contact ospo@kiteworks.com.

> **License status:** This repository is already licensed under Apache-2.0 -- the OSPO target license.
> No migration is required.
