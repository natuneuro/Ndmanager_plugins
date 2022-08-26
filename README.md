NDManager Plugins
=================

NDManager Plugins include a number of scripts and programs to automatically pre-process files recorded with data acquisition systems: file conversion (from vendor-specific, proprietary formats to open formats used by Klusters, Neuroscope and NDManager), channel resampling and reordering, high-pass filtering and spike detection, waveform feature extraction (PCA) for subsequent spike sorting, video transcoding and LED tracking, etc.

Developed by Lynn Hazan and Michaël Zugaro, distributed under the GNU Public License v2.

## Compile guide

### Dependencies

Install following dependencies before compiling NDManager-plugins
```
sudo apt install libxml2-dev xsltproc docbook-xsl libgsl-dev
```
  1. Go to `/NDManager-plugins` directory and type:
  ```
  mkdir build
  cd build
  cmake ..
  make 
  sudo make install
  ```
  2. Update all installed libraries:
  ```
  sudo/sbin/ldconfig -v
  ```
  
