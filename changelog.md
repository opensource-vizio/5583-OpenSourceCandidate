# MediaTek Distro — Open Source Change Log (v5 Distribution)

Release artifact: 5583_oss_build_v5.zip  
Release date: August 13, 2024

## Scope of this release
- This is the only externally distributed build in the v1–v5 series.
- Prior versions (v1–v4) represent internal evolution.

## Package structure (v5)
- btsound-release-legal-5583/
  - 3pty/
  - build_instructions/
  - docker/
  - env.sh
  - kernel/
  - scripts/
  - VERSION
  - README.md
- ffmpg/
  - FFmpeg.gz
  - README.md
- release-5583-20230726-apollo-lite/
  - readme.md
  - release.tar.gz
- release-FUR5.1.1-31X_GPL/
  - docker/
  - platform/
  - README.md
- Build scripts and docs
  - buildApolloLite.sh
  - buildBtsound.sh
  - buildFfmpg.sh
  - buildFUR5.1.1-31X_GPL.sh
  - prepForBuild.sh
  - readme.md

Notes on traceability
- Source and build materials for third-party components are organized under:
  - release-FUR5.1.1-31X_GPL/platform/…
  - btsound-release-legal-5583/3pty/…
- Build scripts at the repository root reproduce packaged artifacts for the apollo-lite, btsound, FFmpeg, and FUR5.1.1-31X_GPL components.

## Changes from prior internal iteration (v4 → v5)
- Restored: release-5583-20230726-apollo-lite/, release-FUR5.1.1-31X_GPL/
- Added: standardized build scripts (buildApolloLite.sh, buildBtsound.sh, buildFfmpg.sh, buildFUR5.1.1-31X_GPL.sh, prepForBuild.sh)
- Consolidated documentation and version files across directories to ensure consistent metadata

## Distribution identifier
- File name: 5583_oss_build_v5.zip
- Date: 08-13-2024

