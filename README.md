# Seam Carving

https://github.com/ocen-lang/seamcarve/assets/9910883/2398b9fe-efca-41c7-951b-399ba9b4b3cf

## Build

> Compilation has only been tested on linux / macOS.

This algorithm is implemented in [ocen](https://github.com/ocen-lang/ocen), and you'll need to [set up the ocen compiler](https://github.com/ocen-lang/ocen#usage). You will also need to have SDL installed and available in your default include / library paths. If you wish to use the `ffmpeg` video output mode, you'll need to have `ffmpeg` available in your PATH.

For input, currently only `.qoi` images are supported. You can use `imagemagick` to convert existing ones you have (`convert foo.png foo.qoi`)

```
$ ocen main.oc -o seamcarve
$ /seamcarve input.qoi
```