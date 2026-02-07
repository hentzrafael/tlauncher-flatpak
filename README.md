# Flatpak Builder for TLauncher

## Steps
1. Clone the repo
2. Install flatpak-builder on your distro
3. Run the build command:
```
flatpak-builder --user --install build-dir com.local.TLauncher.yml --force-clean
```

This will make your app available in your local flatpak registry and allows you to open it from the app menu.

Enjoy :)

Rafael.
