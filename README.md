# The Surgical Image Registration Generator (SIRGn) Video Benchmark

This repository contains an example implementation of the SIRGn video benchmark along with ancilliary examples of video pre-processing steps

The repository is organized as follows:

* [Example SIRGn Implementation](src/SIRGn)
* [Example SIRGn input data](example/data)
* [Example script to generate SIRGn input data from laparoscopic video](example/)
* [Program to convert Laparoscopic Video to a sequence of textured 3D meshes](src/Features)
* [Program to automatically extract video features](src/Features)
* [Source code patch for global non-rigid registration of textured 3D meshes](src/Registration) please see readme for details.


## Paper

```
Benchmarking Video With The Surgical Image Registration Generator (SIRGn) Baseline
Michael Barrow, Nelson Ho, Alric Althoff, Peter Tueller and Ryan Kastner
WACV 2019
```


## License

MIT
