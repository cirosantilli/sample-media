# Media

Small media files that I don't want to pollute my repositories with.

Mainly to test operations on media formats.

1.  Image
    1.  [lenna-512.png](lenna-512.png) Original source:  <https://upload.wikimedia.org/wikipedia/en/2/24/Lenna.png>
1.  Video
    1.  [lego-h264-aac.mp4](lego-h264-aac.mp4) Original source: <http://techslides.com/sample-files-for-development> License: TODO. Created: 2010 (metadata)
    1.  [lego.h264](lego.h264) Extracted from [lego-h264-aac.mp4](lego-h264-aac.mp4) with `ffmpeg -i lego-h264-aac.mp4 -vcodec copy -bsf h264_mp4toannexb -an -f h264 lego.h264`
    1.  [lego.aac](lego.aac) Extracted from [lego-h264-aac.mp4](lego-h264-aac.mp4) with `ffmpeg -i lego-h264-aac.mp4 -c copy -map 0:a:0 lego.aac` See also: <http://superuser.com/questions/186465/extract-audio-aac-from-mp4>
    1.  [lego-vp8-vorbis.webm](lego-vp8-vorbis.webm) Original source: <http://techslides.com/sample-files-for-development> License: TODO. Created: 2010 (metadata)

Good candidates:

- Big Buck Bunny <https://www.youtube.com/watch?v=P5yHEKqx86U> <https://en.wikipedia.org/wiki/Big_Buck_Bunny>, often used by the AOSP.
