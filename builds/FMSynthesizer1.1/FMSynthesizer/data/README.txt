Installation of WaveIO package
==============================
- unpack into  directory of your choice
- choose the correct version of waveio.dll (default is the 32bit version). Rename waveio_x64.dll to waveio.dll, if you run 64bit Labview
- to optimize the VIs and LLB for your Labview version, perform a mass compile (Tools->advanced->mass compile) on the unpacked directory
- either copy the files waveio.dll and waveio.llb into the LabView directory user.lib and restart Labview (the Vis should show up in the function palette under User Libraries)
  or copy waveio.dll and waveio.llb into the directory of your project
- the example VIs should be copied to the working directory of the LabView project

In case of problems send mail: info@zeitnitz.eu

February 2017 Christian Zeitnitz