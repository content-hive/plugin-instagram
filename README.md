# Content Hive Plugin: Instagram

An Instagram content parsing plugin for Content Hive. Fetches post content, images, videos, reels, and author information. Requires authentication via sessionid cookie (private API).

Plugin for [Content Hive](https://github.com/content-hive/content-hive).

## Layout

```
plugin/              # plugin source, installed as plugins/instagram/ by Content Hive
├── manifest.json    # plugin metadata (domain, version, requirements, release_notes)
├── __init__.py
└── ...
contenthive.json     # repository metadata for the Content Hive plugin catalog
```

## Disclaimer

> This plugin fetches content via Instagram APIs. Please ensure compliance with Instagram's Terms of Service and applicable local laws before use. Platform policy changes may cause the plugin to stop working.

## Releasing

1. Bump `version` and rewrite `release_notes` in `plugin/manifest.json`.
2. Merge into `main`.
3. Publish a GitHub Release whose tag is `v<version>` (for example `v0.1.2`).
