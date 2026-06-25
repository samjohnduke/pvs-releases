# PVS — releases

Public download channel for **PVS**, a peer-to-peer app for secret, timed sharing
of text / image / audio / video posts.

> The application **source code lives in a separate private repository**. This repo
> holds only the built binaries, published automatically by CI on each tagged release.

## Install

Linux (x86_64) and macOS (Apple silicon / Intel):

```sh
curl -fsSL https://samjohnduke.github.io/pvs/install.sh | sh
```

The script detects your platform, verifies the download against the release
`SHA256SUMS`, and installs the `pvs` binary to `~/.local/bin`. Or download a tarball
directly from the [releases page](https://github.com/samjohnduke/pvs-releases/releases).

Once installed, the app checks here for new releases on launch and updates itself in
place when you confirm.
