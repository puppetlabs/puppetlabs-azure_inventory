<!-- markdownlint-disable MD024 -->
# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/) and this project adheres to [Semantic Versioning](http://semver.org).

## [v1.0.0](https://github.com/puppetlabs/puppetlabs-azure_inventory/tree/v1.0.0) - 2026-09-10

[Full Changelog](https://github.com/puppetlabs/puppetlabs-azure_inventory/compare/0.5.1...v1.0.0)

### Changed

- (BOLT-193) azure_inventory pdk update to puppet 9 [#18](https://github.com/puppetlabs/puppetlabs-azure_inventory/pull/18) ([gavindidrichsen](https://github.com/gavindidrichsen))


## [v0.5.1]()

### New features

* **Bump ruby_task_helper upper bound to < 2.0.0** ([#16](https://github.com/puppetlabs/puppetlabs-azure_inventory/pull/16))

## Release 0.5.0

### New features

* **Bump maximum Puppet version to include 7.x** ([#14](https://github.com/puppetlabs/puppetlabs-azure_inventory/pull/14))

## Release 0.4.1

### Bug fixes

* **Add PDK as a gem dependency**

  PDK is now a gem dependency for the module release pipeline

## Release 0.4.0

### New features

* **Add debugging statements to task errors**
  ([#9](https://github.com/puppetlabs/puppetlabs-azure_inventory/pull/9))

  Error objects returned from the `resolve_reference` task now includes
  debugging statements that describe the steps the task is taking under
  the `details` key.

### Bug fixes

* **Add missing dependency to module metadata**
  ([#10](https://github.com/puppetlabs/puppetlabs-azure_inventory/pull/9))

  The module metadata now includes `ruby_plugin_helper` and `ruby_task_helper`
  as dependencies.

## Release 0.3.0

### New features

* **Set `resolve_reference` task to private** ([#6](https://github.com/puppetlabs/puppetlabs-azure_inventory/pull/6))

    The `resolve_reference` task has been set to `private` so it no longer appears in UI lists.

## Release 0.2.0

**Changes**

This converts the module to a Bolt plugin, which includes renaming the `inventory_targets` task to `resolve_references`.

## Release 0.1.0

This is the initial release.
