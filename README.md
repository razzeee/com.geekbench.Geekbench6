# Geekbench6 Flatpak

## Building

```
flatpak-builder build-dir --user --ccache --force-clean --install com.geekbench.Geekbench6.yml
```

Then you can run it via the command line:

```
flatpak run com.geekbench.Geekbench6
```

```
flatpak run com.geekbench.Geekbench6 --compute vulkan
```

or just search for the installed app on your system
