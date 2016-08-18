# H.264
This project is a fork of the free x264 codec project http://www.videolan.org/developers/x264.html. Encoding video is a tradeoff between visual quality, encoding speed and file size. This fork is specifically for contexts where encoding speed is not a concern.
The following quick start guide has instructions that help you build the x264 Codec. https://trac.ffmpeg.org/wiki/CompilationGuide/Quick/libx264

# H.264 Features

1. 4:2:0 Sampling Structure   http://www.muratdemirci.com.tr/image.axd?picture=%2F2014%2F10%2F316-F6-Chroma-Subsampling-SECONDARY_1(1).png
2. Variable Block Size motion estimation
3. Multiple Reference Frames http://electronicimaging.spiedigitallibrary.org/data/Journals/ELECTIM/23509/033003_1_1.png
4. Five Slice Types - I, B, P, SP, SI
5. Arbitrary Slice ordering
6. 9 intra prediction modes http://image.slidesharecdn.com/h-140615070101-phpapp01/95/h264-vs-hevc-9-638.jpg?cb=1402815792
7. Sub-pixel (1/4 Pixel) accuracy
8. 5 Motion Estimation Methods http://1.bp.blogspot.com/-LT4HHZFVPCE/UURtzfFxTZI/AAAAAAAAAcU/7wvblqNklwo/s1600/futurama+SD+Percentage+MEM.png
9. Integer Transform
10. Trellis Quantizer
11. CABAC Entropy Encoding
