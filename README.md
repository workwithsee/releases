# S.E.E. releases

S.E.E. is a self-hosted app for running multi-step workflows, including AI coding agents, across your Git repositories. It runs on your computer and opens in your browser.

Choose the installer for your platform and architecture on the [Releases page](https://github.com/workwithsee/releases/releases). Pre-release downloads are public and require no GitHub account or signup. The application source is private.

<!-- release-notes:start -->
Please do not share the pre-release download links.

## Install

<!-- release-notes:linux:start -->
**Linux** — Download the installer from this release and double-click it. Confirm **Run** when asked. S.E.E. installs for your account and opens when setup finishes.
<!-- release-notes:linux:end -->

<!-- release-notes:macos:start -->
**macOS** — Download the `.pkg` installer matching your Mac, open it, and confirm installation. S.E.E. installs for your account and opens when setup finishes. Cancelling before installation leaves the app unchanged.
<!-- release-notes:macos:end -->

The installer sets up S.E.E. for your account without `sudo`. Check the [platform requirements](https://github.com/workwithsee/releases#platform-requirements) before installing.

## Update manually

Finish active work and quit S.E.E. from the tray or menu bar. Download the newer installer and follow the same steps. Your settings and project data are preserved.

## Verify the download

Each Linux release includes detached OpenPGP signatures for the installer, `SHA256SUMS`, and `release-manifest.json`, plus `see-linux-signing-key.asc`. The signing key fingerprint is `62BFE8F1FA6C955DDAEA071231C5CE67E7F7CF58`. These signatures verify the downloaded bytes; your desktop may still ask you to confirm Run.

[S.E.E. website](https://workwithsee.com/) · [License](https://github.com/workwithsee/releases/blob/main/LICENSE)
<!-- release-notes:end -->

## Platform requirements

- **Linux** requires glibc 2.39 or newer, GTK 3, curl, xdg-utils, and a systemd user session. Application runtime libraries are included. The download-and-double-click flow is tested on Ubuntu 26.04 with Xfce. The desktop must offer Run for downloaded `.desktop` application launchers. Desktops that open these files as text are unsupported by this installer.
- **macOS** requires macOS 12 or later. Choose the archive matching your Mac's architecture.
