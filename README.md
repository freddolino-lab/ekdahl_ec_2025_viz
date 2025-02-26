This directory contains an igv session for visualizing data from "Multiscale regulation of nutrient stress responses in Escherichia coli from chromatin structure to small regulatory RNAs"
Please be sure to decompress all of the occpancy files in the occupancy/ subdirectory prior to use. For example:

```
cd occupancy
for f in `ls *bz2` ; do
  bunzip2 $f
done
```
