# Building

To run a build of the flatpak run

```sh
$ flatpak-builder build-dir --force-clean com.snekstudio.Snekstudio.yaml 
```

`--force-clean` can be omitted but you should use this so build-dir is cleaned after a build.

To build and install run
```sh
$ flatpak-builder build-dir --force-clean com.snekstudio.Snekstudio.yaml --user --install
```

In some cases you may need to reboot for the icons to appear in your DE/WM's launcher. To run it from the command line after installing it.

```sh
$ flatpak run com.snekstudio.Snekstudio
```