# nexys_video_mandelbrot
Realtime display (1080i) of Mandelbrot on Nexys Video

# Mandelbrot 1080i for Nexys Video (Artix 200T)

Based on Hamsterworks project
http://hamsterworks.co.nz/mediawiki/index.php/Mandelbrot_NG_1080i

- Has no frame buffer - each pixel is recalculated every time.
- Displays at 1920x1080 resolution
- Smooth real-time pans and zooms
- about 120 billion calculations per second.

Scroll with the North, South, East, West pushbuttons, zoom in/out with 

Centre pushbutton + East/West.

Attach PModENC to Top row of PMod JA as an alternative way to Zoom in/out.
Attach PModJSTK to top row of PMod JB as an alternative way to scroll and zoom. (Zoom in/out with pushbuttons on PModJSTK)

