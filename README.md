# Lumen

A fast LUT preview studio for photographers. Drop in a folder of `.cube`
files, point Lumen at a photo, and see every look at a glance — rendered
for real by a GPU compute shader (with CPU fallback), not approximated.

Windows installer for the latest version is in the
[**Releases**](https://github.com/pierre-thurau/lut-vizualizer/releases)
section.

## What you get

- **Real previews** — every tile is the actual photo with the actual LUT
  applied, not CSS filters.
- **Fast** — six-way parallel render queue, GPU compute shader, mozjpeg
  encoder, in-memory cache that survives rotation.
- **RAW support** out of the box: NEF, CR2/CR3, ARW, RAF, RW2, ORF, SRW,
  DNG.
- **Compare modes**: slider, side-by-side, toggle hold.
- **Batch export** — stage N LUTs, export all as JPEGs in one click.
- **Drag-and-drop a folder** anywhere on the window.
- **Bundled sample LUTs** so you can try it before downloading a pack.
- **Auto-update** via signed releases.
- **Localised** EN + FR. Dark + light themes.

## Installation

1. Download the latest `.msi` or `.exe` from
   [Releases](https://github.com/pierre-thurau/lut-vizualizer/releases/latest).
2. Run it. Windows SmartScreen may warn that the publisher is
   unverified — click "More info → Run anyway". The installer isn't
   yet code-signed (this is a personal project, not a commercial
   product).
3. Open Lumen, drag a folder of `.cube` files onto the window, and pick
   a photo.

## Reporting issues

Bug or feature request? Open one at
[Issues](https://github.com/pierre-thurau/lut-vizualizer/issues).

## License

Dual-licensed under either **MIT** or **Apache-2.0** at your option, for
non-commercial use. The bundled sample LUTs are **CC0 1.0** (public
domain).

## Credits

Created by **Pierre Thurau**. Built with Tauri 2, Svelte 5, Rust, wgpu,
image-rs, and mozjpeg.
