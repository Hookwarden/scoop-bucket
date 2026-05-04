# Hookwarden Scoop Bucket

Scoop bucket for [hookwarden](https://hookwarden.dev) — the webhook signature-verification audit tool.

## Install

    scoop bucket add hookwarden https://github.com/Hookwarden/scoop-bucket
    scoop install hookwarden

## Verify

    hookwarden --version

## Supported platforms

- Windows x64

Pre-built binaries are pulled from [Hookwarden/hookwarden GitHub Releases](https://github.com/Hookwarden/hookwarden/releases). The manifest is auto-updated by hookwarden's release pipeline; users running `scoop update hookwarden` between our pushes pick up new versions via the `autoupdate` block.

## License

Apache-2.0 — see LICENSE.
