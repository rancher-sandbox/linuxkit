# Datasource providers

This is a fork from [linuxkit](https://github.com/linuxkit/linuxkit) including only a refactored version of the
datasource providers logic.

Notable changes are:
* Inclusion of an abandoned [PR](https://github.com/linuxkit/linuxkit/pull/3585).
* The code is refactored so datasource providers are part of an importable golang providers package.
* Few fixes and adaptations have been incorporated to enhance cdrom provider.
* Only datasource providers or the former metadata package code is kept, all ther rest is dropped.
