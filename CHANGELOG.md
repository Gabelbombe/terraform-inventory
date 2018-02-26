# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [1.0.1] - 2018-02-25
### Added
- Support for `ansible_group` resource, added in [nbering/terraform-provider-ansible#8](https://github.com/nbering/terraform-provider-ansible/pull/8)

## [1.0.0] - 2018-01-07
### Added
- Added `ANSIBLE_TF_DIR` environment variable to set Terraform configuration directory.

### Changed
- Ported the script to Python to be more compatible with the Ansible ecosystem.
- Changed `TERRAFORM_PATH` environment variable to `ANSIBLE_TF_PATH`.

### Deprecated
- The earlier NodeJS implementation will not be supported going forward.

## [0.0.2] - 2018-01-06
### Changed
- Update docs and package info for move back to GitHub.

[Unreleased]: https://github.com/nbering/terraform-inventory/compare/v1.0.1...HEAD
[1.0.1]: https://github.com/nbering/terraform-inventory/compare/v1.0.0...v1.0.1
[1.0.0]: https://github.com/nbering/terraform-inventory/compare/v0.0.2...v1.0.0
[0.0.2]: https://github.com/nbering/terraform-inventory/compare/v0.0.1...v0.0.2
