# Changelog

Format based on [Keep a Changelog](https://keepachangelog.com/).

## [0.3.1] - 2026-09-20

### Changed
- StigForge export refresh for `cs10_cis` at `0.3.1`.

### Verified (OpenSCAP)


### Provenance

- Factory pipeline: https://github.com/stigready/stigforge/actions/runs/35529346593
- Factory commit: `9a161e04bbdab156d492c2cb0f6afb2ab43beb30`

## [0.3.0] - 2026-09-12

### Changed
- StigForge export refresh for `cs10_cis` at `0.3.0`.

### Verified (OpenSCAP)

- **`cis-l1`** — score **96.3%** (floor 90.0%) · gate **PASS** · evidence `20260912T124221Z`
  - Remaining counted failures: `ensure_redhat_gpgkey_installed, no_files_or_dirs_ungroupowned, use_pam_wheel_group_for_su`
- **`cis-l2`** — score **96.47%** (floor 90.0%) · gate **PASS** · evidence `20260912T124440Z`
  - Remaining counted failures: `ensure_redhat_gpgkey_installed, no_files_or_dirs_ungroupowned, use_pam_wheel_group_for_su`
- **`cis-ws-l1`** — score **96.3%** (floor 90.0%) · gate **PASS** · evidence `20260912T124609Z`
  - Remaining counted failures: `ensure_redhat_gpgkey_installed, no_files_or_dirs_ungroupowned, use_pam_wheel_group_for_su`
- **`cis-ws-l2`** — score **96.43%** (floor 90.0%) · gate **PASS** · evidence `20260912T124824Z`
  - Remaining counted failures: `ensure_redhat_gpgkey_installed, no_files_or_dirs_ungroupowned, use_pam_wheel_group_for_su`

### Provenance

- Factory pipeline: https://github.com/stigready/stigforge/actions/runs/34693316989
- Factory commit: `562a1f7c1a8e19235ee26e972174d1be6c88998c`

## [0.2.4] - 2026-07-31

### Added
- Initial StigForge export of matrix role `cs10_cis`.
- OpenSCAP verify evidence bundles per profile under `compliance/releases/`.

### Verified (OpenSCAP)

- **`cis-l1`** — score **96.3%** (floor 90.0%) · gate **PASS** · evidence `20260731T090325Z`
  - Remaining counted failures: `configure_custom_crypto_policy_cis, ensure_redhat_gpgkey_installed, use_pam_wheel_group_for_su`
- **`cis-l2`** — score **95.29%** (floor 90.0%) · gate **PASS** · evidence `20260731T090605Z`
  - Remaining counted failures: `configure_custom_crypto_policy_cis, disable_weak_deps, ensure_redhat_gpgkey_installed, use_pam_wheel_group_for_su`
- **`cis-ws-l1`** — score **96.3%** (floor 90.0%) · gate **PASS** · evidence `20260731T090752Z`
  - Remaining counted failures: `configure_custom_crypto_policy_cis, ensure_redhat_gpgkey_installed, use_pam_wheel_group_for_su`
- **`cis-ws-l2`** — score **95.24%** (floor 90.0%) · gate **PASS** · evidence `20260731T091030Z`
  - Remaining counted failures: `configure_custom_crypto_policy_cis, disable_weak_deps, ensure_redhat_gpgkey_installed, use_pam_wheel_group_for_su`

### Provenance

- Factory pipeline: https://github.com/stigready/stigforge/actions/runs/30617333526
- Factory commit: `5c2fc8f5ad23bdd66e77fe95e1363d5a10c9f05d`

## [0.2.1-private-review] - 2026-07-28

### Changed
- Galaxy-style layout: Ansible role at repository root; evidence under `compliance/`.
- Private review tag `v0.2.1-private-review` (supersedes nested `roles/<role>/` export).

## [0.2.0-private-review] - 2026-07-26

### Added
- First private StigForge export to `stigready/*` (factory review; nested role path).
