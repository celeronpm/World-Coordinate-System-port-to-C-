Wold Coordinate System .NET Port
========

As part of the NASA Asteroid Data Hunter TopCoder Challenge, we have had to deep dive into and learn a lot about astronomy.

The challenge exposes FITS (Flexible Image Transport System) data sets to the challenger. The FITS data set contains a number of World Coordinate System data points such as

  - Right Ascension
  - Declination
  - X,Y reference pixels
  - X,Y coordinate increments,
  - Rotation in degreen
  - Projection type (e.g. tan, sin, etc)
  - X,Y reference pixel coordinates , etc..
  - Using this information one can extrapolate RA(right ascension) and Declination of any pixel on an astronomical image. Inversely, one can map an RA/Dec value to a pixel.

Since we prefer to develop on the .NET platform we had a hard time finding any algorithms/libraries to help with this task. We ended up porting the WCSTools library, specifically for the pixel to RA/Dec algorithms, to C#/.NET



## License

    Copyright 2014 Marius Dornean (MariusSoft LLC) + License included in .cs file

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
