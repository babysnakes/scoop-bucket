# BabysnakesDev Scoop Bucket

<!-- Uncomment the following line after replacing placeholders -->
[![Tests](https://github.com/babysnakes/scoop-bucket/actions/workflows/ci.yml/badge.svg)](https://github.com/babysnakes/scoop-bucket/actions/workflows/ci.yml) [![Excavator](https://github.com/babysnakes/scoop-bucket/actions/workflows/excavator.yml/badge.svg)](https://github.com/babysnakes/scoop-bucket/actions/workflows/excavator.yml)

This is my [Scoop](https://scoop.sh) bucket, containing manifests of my open source projects.

## Available Manifests

- [dot-local-dns](https://github.com/babysnakes/dot-local-dns/)
- [roon-tagger-dev](https://github.com/babysnakes/roon-tagger) - An old pre-release of Roon-Tagger (actually quite stable, but limited)
- [glazewm-tray](https://github.com/babysnakes/GlazeWM-Tray/)

## How do I install these manifests?

Identify the manifest you want to use and run:

```pwsh
scoop bucket add BabysnakesDev https://github.com/babysnakes/scoop-bucket
scoop install BabysnakesDev/<manifestname>
```

