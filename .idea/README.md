
[comment]: <> (while on Serious Sam Fusion 2017 the trailer went black on full screen. ughhhhh)

[comment]: <> (lets create a checker for when a trailer is playing we check the server thats outputting the video feed of steam. This checker will look for rgb colors in the full screen mode of steam. )

[comment]: <> (    - we click play in steam program runs for 4 seconds)

[comment]: <> (    - if steamPID == fullscreen check for resoluitonWidth, resolutionHeight for resoluitonWidth * resolutionHeight / 3 = TooMany)

[comment]: <> (    - TooMany > hex#000000 { exitFullscreen })

