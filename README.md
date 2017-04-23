miniMandelbrot
==

A Mandelbrot set tracer on a canvas in less than 256b

Golfed with @Xen_the, @keithclarkcouk, @veubeke, @joseprio @subzey @aemkei @p01 @FireyFly @siorki...

- Big, zoomable with click, commented source code: http://xem.github.io/miniMandelbrot/big.html

- Super mini version: http://xem.github.io/miniMandelbrot/index.html (143b) (may freeze your browser for ~30 seconds)

- Tweet: https://twitter.com/MaximeEuziere/status/843397121369956354

- Best tweetable version: http://xem.github.io/miniMandelbrot/index2.html (194b)

- Tweet: https://twitter.com/MaximeEuziere/status/843812580569374720

- 140b version by xen (a bit zoomed and cropped, and longer to execute, but hey, 140b!):

````
<canvas id=A><svg onload=for(P=Q=5e4;Q--;A.getContext`2d`.fillRect(Q%X,Q/X,1,I/X))for(V=W=0,X=I=297;I--/V;W=Z+Z+Q/P)Z=V*W,V=V*V-W*W+Q/X%1-1>
````
