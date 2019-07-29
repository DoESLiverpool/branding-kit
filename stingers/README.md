# Stingers

Each directory contains an AEP (After Effects Project) file, along with any files the project file expects in its path. Included is the stinger footage in a 7z archive since the output file for this kind of content is small enough. 

The compression ratio on this format [Apple ProRes 4444](https://en.wikipedia.org/wiki/Apple_ProRes) is quite subtantial, so it is highly preferable if any future projects that are compiled keep the output video file in a 7z archive with maximum lzma2 compression. As an example, the doesliverpool stinger is 6.4MiB before compression, 401.3KiB afterwards.

# Modifying and Usage

**More documentation coming soon**

The `logo.png` in the doesliverpool stinger can be replaced with a logo of your choosing to generate a suitable stinger for usage with with your own logo. 

There is also a requirement to export this in the proper format (Apple Prores 4444) to correctly export the alpha channel (transparency) of your video. If you don't export the alpha channel you will not be able to use the output as a scene transition as intended. since there will be no transparency and the background will be black.

