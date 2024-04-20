# Screenshot

Screenshot tool for CutefishOS.

## OpenMandriva Dependencies

```shell
sudo dnf in task-develop
sudo dnf install extra-cmake-modules
```

## Build

```shell
mkdir build
cd build
cmake -DCMAKE_INSTALL_PREFIX:PATH=/usr ..
make
```

## Install

```shell
sudo make install
```

## Uninstall

```shell
rm /usr/bin/cutefish-screenshot
rm /usr/share/applications/cutefish-screenshot.desktop
```

## License

This project has been licensed by GPLv3.
