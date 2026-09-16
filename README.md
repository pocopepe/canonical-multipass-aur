# canonical-multipass-aur

A build-and-verify setup for the `canonical-multipass` AUR package — bumps it to multipass 1.16.4, fixes the build failure it's currently flagged for, and patches a handful of compile breaks that show up when building against a modern Arch toolchain. Run the "Verify PKGBUILD" workflow manually to spin up a clean Arch container and confirm the package still builds end to end.
