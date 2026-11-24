# S.E.E. releases

S.E.E. is a self-hosted app for running multi-step workflows, including AI coding agents, across your Git repositories. It runs on your computer and opens in your browser.

Choose the archive for your platform and architecture on the [Releases page](https://github.com/workwithsee/releases/releases). Pre-release downloads are public and require no GitHub account. The application source is private.

<!-- release-notes:start -->
## Install

1. Download and extract the installer archive for your platform.
2. Open a terminal in the extracted directory and run `bash install-user.sh` as your regular user.
3. Open S.E.E. from your Linux applications menu or your macOS Applications folder.

The installer sets up S.E.E. for your account without `sudo`. Check the [platform requirements](https://github.com/workwithsee/releases#platform-requirements) before installing.

## Update manually

Finish active work and quit S.E.E. from the tray or menu bar. Extract the new archive and run its installer. Your settings and project data are preserved.

## Verify the download

Each release includes `SHA256SUMS` and `release-manifest.json`. Use `SHA256SUMS` to verify the installer archive and manifest.

[S.E.E. website](https://workwithsee.com/) · [License](https://github.com/workwithsee/releases/blob/main/LICENSE)
<!-- release-notes:end -->

## Platform requirements

- **Linux** uses a glibc-based desktop with a systemd user session. The installer requires GTK 3, WebKitGTK 4.1, Ayatana AppIndicator, libxdo, curl, and xdg-utils.
- **macOS** requires macOS 12 or later. Choose the archive matching your Mac's architecture.
