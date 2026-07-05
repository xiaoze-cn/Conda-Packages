# Conda Channel

Static conda channel for SDK files, runtime bundles, and development tools.

Channel URL: `https://xiaoze-cn.github.io/conda-channel`

## Layout

```text
C:\Projects\Development Tools\Conda Channel
├── README.md
├── index.html
├── noarch
│   └── repodata.json
├── win-64
│   ├── hikcamera-mvs-5.0.1-20260512_0.conda
│   └── repodata.json
└── linux-64
    └── repodata.json
```

## Files

- `*.conda`: package archives installed by conda-compatible tools.
- `repodata.json`: readable package index for each platform.
- `.tmp/`: local build output, ignored by git.

## Packages

- `win-64/hikcamera-mvs-5.0.1-20260512_0.conda`: HikCamera MVS 5.0.1 SDK files for Windows x86_64.
