# WiFeS-RM

This repository contains four jupyter notebooks used for reverberation mapping with spectroscopic data from WiFeS and photometry from LCO.
It contains:
1. Stitching pipeline, which takes in WiFeS data and stitches the red and blue sides together, as well as performing background correction
2. Photometry pipeline, which takes LCO photometry and modifies the file format
3. WiFeS calibSpec - performs photometric calibration of the WiFeS spectra. Modified from the original OzDES program by Janie Hoormann (https://github.com/jhoormann/OzDES_calibSpec)
4. WiFeS makeLC - calculates line fluxes and makes light curves. Modified from original OzDES program by Janie Hoormann (https://github.com/jhoormann/OzDES_makeLC)

In order for these to run, you need:
Reduced WiFeS observations (.p11.fits)
Reduced LCO photometry observations (.csv)
List of source names in .txt file
List of source names and redshifts in .txt file
Filter transmission functions for each filter in a two column format, wavelength (nm) and transmission fraction (range 0-1), in a .dat file

Please contact u6066740@anu.edu.au if you would like further assistance in implementing the WiFeS RM code

### Please note that the OzDES calibSpec and makeLC pipelines are copyrighted by Janie Hoormann with the following notice:

MIT License

Copyright (c) 2019 Janie K. Hoormann

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
