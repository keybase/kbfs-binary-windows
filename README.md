# kbfs-binary-windows

Binaries required for building kbfs on windows

dokan1.lib is the import library for x86 (32bit) Dokan.
The binary is obtained from https://dokan-dev.github.io/
and the sources are on https://github.com/dokan-dev/dokany

Currently with 1.0.0rc2 sha1-sum is:
```
8fcfe265c5558fba9fc6bff4af8bb0b83a159611  dokan1.lib
```

Always tag with the required version.

For example, tag dokan-v0.8.0-RC4 is attached to dokan.lib version v0.8.0-RC4, with a sha1 of: 96cf91e81e8c983aea04fcdd1d9e53ed699d6c7c.

The appveyor script in kbfs should be updated accordingly.
