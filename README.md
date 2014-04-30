[![Build Status](https://drone.io/github.com/cboxdoerfer/ddb_spectrogram/status.png)](https://drone.io/github.com/cboxdoerfer/ddb_spectrogram/latest)

Spectrogram plugin for DeaDBeeF audio player
====================

## Installation

### Arch Linux
See the [AUR](https://aur.archlinux.org/packages/deadbeef-plugin-spectrogram-git/)

### Gentoo
See ebuilds [here](https://github.com/megabaks/stuff/tree/master/media-plugins/deadbeef-spectrogram)

### Binaries

#### Dev
[x86_64](https://drone.io/github.com/cboxdoerfer/ddb_spectrogram/files/deadbeef-plugin-builder/ddb_spectrogram_x86_64.tar.gz)

[i686](https://drone.io/github.com/cboxdoerfer/ddb_spectrogram/files/deadbeef-plugin-builder/ddb_spectrogram_i686.tar.gz)

Install them as follows:

x86_64: ```tar -xvf ddb_spectrogram_x86_64.tar.gz -C ~/.local/lib/deadbeef```

i686: ```tar -xvf ddb_spectrogram_i686.tar.gz -C ~/.local/lib/deadbeef```

### Other distributions
#### Build from sources
First install DeaDBeeF (>=0.6) and fftw3
```bash
make
./userinstall.sh
```

## Screenshot

![](http://i.imgur.com/UTEVqr3.png)
