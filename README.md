# drupal7-video-ffmpeg2.8-presets #

## Fine tuned compilation of Drupal Media Video encoder Presets ##

### Requeriments ###
- Tested on FFMpeg 2.6, 2.7, 2.8 (Compiled with all Privative Codecs).
- Tested over "video" Development and Recommended module releases

You can check codec availability issuing ffmpeg on command line, to get working this presets will output that configuration
```
--enable-libspeex --enable-libtheora --enable-libvorbis --enable-libmp3lame --enable-libvpx --enable-libx264 --enable-libx265
```
(If doesnt appears any of that parameters you will have some encoding issues)

- Fedora: install ffmpeg from rpmfusion repositories
- Debian: install ffmpeg from deb-multimedia repositories
