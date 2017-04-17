# ghost script
convert from eps to png
## Install
- ubuntu
```
sudo apt-get install ghostscript -y
```
- run
```
gs -dSAFER \
   -dBATCH \
   -dNOPAUSE \
   -dEPSCrop \
   -dEPSFitPage \
   -sDEVICE=png16m \
   -r150 \
   -g1000x1000 \
   -sOutputFile=2.png 1.eps
```

- source https://ghostscript.com/doc/8.54/Use.htm#Output_device