# heic-to-jpeg

A batch converter for HEIC/HEIF images created on iOS 11 devices

Docker image available here: https://hub.docker.com/r/wshelley/heic-to-jpeg/

The following command will convert all HEIC images in the mounted volume specified:

`docker run -v /path/to/convert/:/convert/ wshelley/heic-to-jpeg`

Based on https://github.com/monostream/tifig
