# Dune Kernel download files

Kernel and checksum manifest for the Dune Kernel APK. The APK also bundles these driver files for offline preparation.

- `hkkernal.sh`: ARM64 executable, run directly (not with `sh`).
- `kernel-manifest.json`: version, URL and SHA256.
- `drivers/catalog.json`: four driver families, 73 files, SHA256 and upstream Git blob provenance.

Upstream driver binaries: https://github.com/leomessilibra45/loader-files

A version match does not guarantee module compatibility. Drivers require a compatible rooted kernel. Only the available `driver_a.kpm` is included; import it in a compatible KernelPatch/APatch manager.

No keys, account credentials or private application source are published here.
