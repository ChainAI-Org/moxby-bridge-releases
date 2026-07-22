# Moxby Bridge releases

Signed installers, updater artifacts, and manifests for the stock-Tauri Moxby
Bridge desktop app.

- `staging-update.json` is updated only after all four staging artifacts and
  their updater signatures have been verified and the prerelease is public.
- `update.json` is reserved for the eventual production Bridge channel.
- Legacy Moxby Agent/CEF artifacts remain in `moxby-agent-releases`; they must
  not be published here.

Release assets are produced by the source repository's GitHub Actions workflows.
