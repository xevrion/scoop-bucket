# HatchZip Scoop bucket

[![Tests](https://github.com/xevrion/scoop-bucket/actions/workflows/ci.yml/badge.svg)](https://github.com/xevrion/scoop-bucket/actions/workflows/ci.yml) [![Excavator](https://github.com/xevrion/scoop-bucket/actions/workflows/excavator.yml/badge.svg)](https://github.com/xevrion/scoop-bucket/actions/workflows/excavator.yml)

The official [Scoop](https://scoop.sh) bucket for [HatchZip](https://hatchzip.dev), which extracts huge archives in place, without needing room for both the archive and its contents.

```powershell
scoop bucket add xevrion https://github.com/xevrion/scoop-bucket
scoop install xevrion/hatchzip
```

This installs the `hatchzip` command line tool and its short name `hz`. For the desktop app and the right-click menu, use the Windows setup from [hatchzip.dev](https://hatchzip.dev).

The manifest is generated from [`packaging/scoop`](https://github.com/xevrion/hatchzip/tree/main/packaging/scoop) in the main repository and kept current by the Excavator workflow. Report problems at [xevrion/hatchzip](https://github.com/xevrion/hatchzip/issues).
