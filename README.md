# ![icon](data/images/icon.png) Quilter

## Focus on your writing
[![License: GPL v3](https://img.shields.io/badge/License-GPL%20v3-blue.svg)](http://www.gnu.org/licenses/gpl-3.0)

![Screenshot](data/images/shot.png)

## License

Fonts under the `/data/font` directory are under [License: SIL OFL 1.1](http://scripts.sil.org/OFL), also copied there in full.

## Dependencies

Please make sure you have these dependencies first before building.

```bash
valac
libgranite-dev
libgtkspell3-3-dev
gtk+-3.0
gtksourceview-3.0
libwebkit2gtk-4.0-dev
libmarkdown2-dev
libgtkspell3-3-dev
meson
```

## Building

Simply clone this repo, then:

```bash
meson build --prefix=/usr && cd build
sudo ninja install
```
