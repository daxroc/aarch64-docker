# Docker images for ARM v8 / aarch64

## FPM 
This image depends on the dcroche/aarch64/ruby container as a base

### Building
```
cd fpm/ 
docker build .
tag <output-tag-id> dcroche/aarch64.fpm
```

### Usage
```
docker run --rm -ti -v /host/working/dir:/data dcroche/aarch64/fpm
```
The above command will place you inside the data directory bound to the host directory.

The fpm command can be used as expected.

