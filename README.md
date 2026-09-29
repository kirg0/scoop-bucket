# kirg0/scoop-bucket

[Scoop](https://scoop.sh) bucket for [d9c](https://github.com/kirg0/d9c) — a terminal UI for
managing Docker on remote hosts over TCP or SSH.

```powershell
scoop bucket add kirg0 https://github.com/kirg0/scoop-bucket
scoop install d9c
scoop update d9c
```

`bucket/d9c.json` (x64 and ARM64) is generated and committed automatically by the
[d9c release workflow](https://github.com/kirg0/d9c/blob/main/.github/workflows/release.yml)
on every release — do not edit it by hand.
