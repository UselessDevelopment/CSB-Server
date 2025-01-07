# Slow Block
Idea by: dqepb, livent, bastard.

# Building
libs
```
sudo apt install build-essential cargo cmake git glslang-tools google-mock libavcodec-extra libavdevice-dev libavfilter-dev libavformat-dev libavutil-dev libcurl4-openssl-dev libfreetype6-dev libglew-dev libnotify-dev libogg-dev libopus-dev libopusfile-dev libpng-dev libsdl2-dev libsqlite3-dev libssl-dev libvulkan-dev libwavpack-dev libx264-dev python3 rustc spirv-tools
```

# Build
```
    mkdir build && cd build
    cmake .. -DCLIENT=OFF
    make
```
