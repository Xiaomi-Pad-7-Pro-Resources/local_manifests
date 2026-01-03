# Local Manifest for Xiaomi Pad 7 Series

This repository contains local manifest files for Android ROM building, organized by device codename and ROM name.

## Branch Format

```
device-codename/romname-version
```

**Example:** `muyu/lineage-23.0`

## Usage

### 1. Navigate to ROM Source Directory

```bash
cd /path/to/rom/source
```

### 2. Clone Local Manifest

```bash
git clone https://github.com/Xiaomi-Pad-7-Pro-Resources/local_manifests.git -b muyu/lineage-23.0 .repo/local_manifests
```

Replace `muyu/lineage-23.0` with your desired device-codename/romname-version branch.

### 3. Sync Repositories

```bash
repo sync -j$(nproc --all)
```

## Branch Naming Convention

- `device-codename/romname-version`
- Examples:
  - `muyu/lineage-23.0`
  - `uke/lineage-23.0`

Each branch contains the specific manifest for that device and ROM combination.

## Building

For complete build instructions, refer to the official build guide of your ROM.
