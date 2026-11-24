# S.E.E. releases

S.E.E. is a self-hosted app for running multi-step workflows, including AI coding agents, across your Git repositories. It runs on your computer and opens in your browser.

Choose the installer for your platform and architecture on the [Releases page](https://github.com/workwithsee/releases/releases). Pre-release downloads are public and require no GitHub account or signup. The application source is private.

<!-- release-notes:start -->
Please do not share the pre-release download links.

## Install

<!-- release-notes:linux:start -->
**Linux** — Download and open the `.flatpak` file in GNOME Software. Choose the **User** source, click **Install**, then click **Open**. If Software does not show Open, launch **S.E.E. Installer** from your applications menu. After setup, launch S.E.E. from your applications menu.
<!-- release-notes:linux:end -->

<!-- release-notes:macos:start -->
**macOS** — Download and extract the ZIP. Open a terminal in the extracted directory and run `bash install-user.sh` as your regular user. Open S.E.E. from your Applications folder.
<!-- release-notes:macos:end -->

The installer sets up S.E.E. for your account without `sudo`. Check the [platform requirements](https://github.com/workwithsee/releases#platform-requirements) before installing.

## Update manually

Finish active work and quit S.E.E. from the tray or menu bar. Download the newer installer and follow the same steps. Your settings and project data are preserved.

## Verify the download

Each release includes `SHA256SUMS` and `release-manifest.json`. Use `SHA256SUMS` to verify the download and manifest.

[S.E.E. website](https://workwithsee.com/) · [License](https://github.com/workwithsee/releases/blob/main/LICENSE)
<!-- release-notes:end -->

## Platform requirements

- **Linux** uses a glibc-based desktop with GNOME Software, its Flatpak support, and a systemd user session. The installer requires GTK 3, WebKitGTK 4.1, Ayatana AppIndicator, libxdo, curl, and xdg-utils.
- **macOS** requires macOS 12 or later. Choose the archive matching your Mac's architecture.
