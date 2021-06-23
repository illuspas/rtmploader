# rtmploader

## Intro
Ultra high concurrent RTMP loader
## Download
### windows
https://cdn.nodemedia.cn/rtmploader/0.3.2/rtmploader_windows_amd64.zip
### linux amd64
https://cdn.nodemedia.cn/rtmploader/0.3.2/rtmploader_linux_amd64.tar.gz
### linux arm64
https://cdn.nodemedia.cn/rtmploader/0.3.2/rtmploader_linux_arm64.tar.gz
### darwin
https://cdn.nodemedia.cn/rtmploader/0.3.2/rtmploader_darwin_amd64.tar.gz
## Usage
### rtmp play loader
./rtmploader -r rtmp://192.168.0.2/live/stream -c 10000

### rtmp play loader
./rtmploader -r rtmp://192.168.0.2/live/stream_{i} -c 1000
>input rtmp://192.168.0.2/live/stream_0 ---- rtmp://192.168.0.2/live/stream_990

### rtmp publish loader
./rtmploader -r rtmp://192.168.0.2/live/stream -c 1000 -f file_name.flv
>output rtmp://192.168.0.2/live/stream_0 --- rtmp://192.168.0.2/live/stream_999
