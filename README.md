# WebGL-simple-video-rendering

Yet another WebGL "Hello World", quickly implemented to test WebGL rendering perfomance and get used to the key concepts.
Actually, it's a Mozilla's [Sample](https://developer.mozilla.org/en-US/docs/Web/API/WebGL_API/Tutorial/Animating_textures_in_WebGL), 
I just changed rotating cube into a simple square surface. 

Launched by a simple `python -m http.server` command, allowing to access video file from the lightweight localhost server.

Proper vieport configuration, depending on video aspect ratio should be added, didn't bother myself with it, because video stream displaying 
requires 3rd-party libraries, thus reducing the sample's value when messing with RTSP stream (my initial goal).
