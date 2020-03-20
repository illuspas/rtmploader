# rtmploader

## Intro
Ultra high concurrent RTMP loader
## Download
### linux amd64
https://github.com/illuspas/rtmploader/releases/download/v0.2.0/rtmploader_linux_amd64.tar.gz
### linux arm64
https://github.com/illuspas/rtmploader/releases/download/v0.2.0/rtmploader_linux_arm64.tar.gz
### windows
https://github.com/illuspas/rtmploader/releases/download/v0.2.0/rtmploader_windows_amd64.zip
### darwin
https://github.com/illuspas/rtmploader/releases/download/v0.2.0/rtmploader_darwin_amd64.tar.gz
## Usage
### rtmp play loader
./rtmploader -r rtmp://192.168.0.2/live/stream -c 10000

### rtmp publish loader
./rtmploader -r rtmp://192.168.0.2/live/stream -c 1000 -f file_name.flv
>output rtmp://192.168.0.2/live/stream_0 --- rtmp://192.168.0.2/live/stream_999
