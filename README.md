# Local manifests for building crDroid 12.X for a54x (Exynos 1380)

Includes hardware repos, Device trees, Vendor trees, and the kernel source.

# How to use it?

1. Copy `local_manifest.xml` to `$TOP/.repo/local_manifests`
2. Sync

## NOTE: After syncing, run `git submodule update --init` in `kernel/samsung/s5e8835` to initialize KernelSU-Next in the kernel (repo sync doesn't do that automatically).
