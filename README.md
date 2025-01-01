# SessionModManager-flatpak
Build out a flatpak version of Session Mod Manager

build and install the flatpak
```
flatpak-builder build-dir --user --install-deps-from=flathub --download-only com.github.rodriada000.SessionMapSwitcher.yaml
flatpak-builder build-dir --user --force-clean --install --repo=repo com.github.rodriada000.SessionMapSwitcher.yaml
```

icon grabbed from official repo, not mine
this is licensed MIT same as main project
