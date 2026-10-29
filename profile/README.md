# NSIS Community

A home for third-party [NSIS](https://nsis.sourceforge.io/) plug-ins, headers and other contributions, most of which were previously hosted on the [NSIS wiki](https://nsis.sourceforge.io/Category:Plugins). Each one gets its own repository, builds in CI and is published as a release.

## Repositories

Repository names start with a prefix that tells you what kind of package they contain:

| Prefix     | Contents                                                             | Example                                                                |
| ---------- | -------------------------------------------------------------------- | ---------------------------------------------------------------------- |
| `plugin-*` | Plug-ins: DLLs built from source, or prebuilt where no source exists | [plugin-nsprocess](https://github.com/nsis-community/plugin-nsprocess) |
| `header-*` | Headers: `.nsh` files with macros and functions                      |                                                                        |
| `misc-*`   | Everything else, such as graphics, language files or tools           |                                                                        |

After the prefix comes the package name in lowercase, for example `nsProcess` → `plugin-nsprocess`.

Every package repository follows the [NSIS Package Layout Specification](https://github.com/nsis-dev/release-package/blob/main/SPEC.md), so releases unpack straight into an NSIS folder.

## Developers

Building this organization's repositories is a step toward moving away from the current SourceForge-hosted infrastructure. It could also become the foundation for installing NSIS plug-ins programmatically. For that to work, packages need to follow shared conventions, such as the [aforementioned specification](https://github.com/nsis-dev/release-package/blob/main/SPEC.md).

This isn't about taking anyone's work away. If one of your plug-ins has been ported here, you're warmly invited to adopt it and carry it forward: just open an issue in its repository and we'll transfer it to you. Already host your plug-in on GitHub? You're welcome to keep your repository and apply the same conventions so it can fit into the same ecosystem.

## Links

- [migration-status](https://github.com/nsis-community/migration-status): build status of every migrated package
- [skills](https://github.com/nsis-community/skills): agent skills for laying out NSIS packages
