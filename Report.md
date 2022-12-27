# Scan Matching Localization

AN ICP algorithm is implemented.

Initially the error did not lay below the required value, this was due to setting the epsilon low at 1e-3, to make a quick convergence. 
[![watch the video](https://img.youtube.com/vi/ppNl5pLhqtw/hqdefault.jpg)](https://youtu.be/ppNl5pLhqtw)

On the second iteration, the epsilon is set lower, and also the resolution was increased. Though the computation is increased for this setup, the error fell below the required quantity.
[![watch the video](https://img.youtube.com/vi/8_W9tljEURU/hqdefault.jpg)](https://youtu.be/8_W9tljEURU)

On the third iteration, by tuning the parameters, the max error was further reduced. The main changes made is the increase of the resolution, thus increasing the computation.
[![watch the video](https://img.youtube.com/vi/PciluAvMBxQ/hqdefault.jpg)](https://youtu.be/PciluAvMBxQ)