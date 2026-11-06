> [!IMPORTANT]
> Builds [maelmsss/exynos982x_kernel](https://github.com/maelmsss/exynos982x_kernel) (Linux 4.14, Exynos 9820 / 9825) with BakaSU and SUSFS.
>
> Devices: Galaxy S10e, S10, S10+, S10 5G, Note10, Note10+. OneUI 7/8/8.5/9

### Workflows
- [build-samsung-note10-oneui-a15.yml](.github/workflows/build-samsung-note10-oneui-a15.yml) builds the whole series.
- [build-samsung-note10plus-oneui-a15.yml](.github/workflows/build-samsung-note10plus-oneui-a15.yml) builds only Note10+ (`d2s`).
- [build-release.yml](.github/workflows/build-release.yml) can run either workflow, or both.

Kernel source, branch `main`, defconfig `exynos9820_defconfig`. SUSFS is `Patches/Patch/susfs_patch_to_4.14.patch`. The inline hook is `Patches/susfs_inline_hook_patches.sh`.

### Copyright
- [BakaSU](https://github.com/Baka-SU/BakaSU)
- [SUSFS](https://gitlab.com/simonpunk/susfs4ksu)
- [Baseband Guard](https://github.com/vc-teahouse/Baseband-guard)
- [NoMount](https://github.com/maxsteeel/nomount)
- [vpnhide_next_backend](https://github.com/soranerai/vpnhide_next_backend)
