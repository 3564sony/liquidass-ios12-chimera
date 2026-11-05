# LiquidAss iOS 12 Chimera Compatibility Fork

This is an experimental rootful/legacy compatibility fork of [winaviation-tweaks/liquidass](https://github.com/winaviation-tweaks/liquidass) for Chimera/Sileo on iOS 12.x.

## Add to Sileo

```text
https://3564sony.github.io/liquidass-ios12-chimera/repo/
```

Install Liquid (Gl)ass from the repo. The package targets `iphoneos-arm`, requires firmware `12.0` through below `13.0`, and is intended for a rootful Chimera environment.

## Important warning

The upstream tweak was written for iOS 14+. This fork changes package constraints, rootful target assumptions, and Mach-O minimum OS metadata, then re-signs the binaries. It was not compiled and tested on a physical iOS 12.5.8 device in this environment. Some hooks may fail or crash SpringBoard. Keep SSH/Safe Mode access available before testing.
