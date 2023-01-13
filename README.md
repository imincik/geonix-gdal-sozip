Run `nix develop github:imincik/geonix-gdal-sozip` to launch the environment.

```
nix develop github:imincik/geonix-gdal-sozip

[geonix] /tmp > gdalinfo --version
GDAL 3.7.0dev, released 2023/99/99

[geonix] /tmp > python -c "import fiona; fiona.show_versions()"
Fiona version: 1.8.22
GDAL version: 3.7.0dev
PROJ version: 9.1.1

OS: Linux 5.15.86
Python: 3.10.9
Python executable: '/nix/store/322rzab91gdcdbkqnsv2p6af7a4vjmq8-python3-3.10.9-env/bin/python3.10'
```
