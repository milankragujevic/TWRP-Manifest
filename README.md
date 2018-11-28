# TWRP Manifest

```
repo init -u https://github.com/milankragujevic/TWRP-manifest.git -b master
```
```
repo sync 
```

## BUILDING FOR ALCATEL 1X 5059D 

```
$ cd [twrp source which synced from above]

$ source build/envsetup.sh 

$ lunch omni_5059d-userdebug 

$ make clean && make -j# recoveryimage  [# : no. of cpu cores ] 
```
