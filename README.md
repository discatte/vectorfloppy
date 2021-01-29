        |o|,.,.,.,.,.,.,.,.,.,.,.,.,.,.,.,.,|o|
        |o|             _______             |o|
        |o|            ||     ||            |o|
        |o|            ||=OwO=||            |o|
        |o|            ||_____||            |o|
        |o|            \_||__|_|            |o|
        |o|                                 |o|
        |o|---------------------------------|o|
        |o|       discatte svg source       |o|
        |o|---------------------------------|o|
        |o|        - Requirements -         |o|
        |o|  Inkscape or libRSVG            |o|
        |o|---------------------------------|o|
        |o|                                 |o|
        |o|      Courtesy of Discatte       |o|
        |o|             and the             |o|
        |o| Intergalactic Transistor Lounge |o|
        |o|                &                |o|
        |o|         Cyber Cat-Cafe          |o|
        |o|                                 |o|
        |o|              01/28              |o|
        |o|,.,.,.,.,.,.,.,.,.,.,.,.,.,.,.,.,|o|

To rasterize discatte (or any SVG) in low resolution pixelized form.
* Add `shape-rendering="crispEdges"` to the root `<svg>` tag
* Run `rsvg-convert -h 118 -f png -o cat.png catdisk-borderless.svg `
