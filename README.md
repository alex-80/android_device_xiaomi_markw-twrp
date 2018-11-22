# treble twrp for xiaomi redmi 4 prime (markw)
## Getting Started ##
---------------


To initialize your local repository using the OMNIROM trees to build TWRP, use a command like this:
```bash
    repo init -u git://github.com/minimal-manifest-twrp/platform_manifest_twrp_omni.git -b twrp-8.1
```

Then to sync up:
```bash
    repo sync
```

Then to build:
```bash
     cd <source-dir>; 
     export ALLOW_MISSING_DEPENDENCIES=true; 
     export LC_ALL=C;
     . build/envsetup.sh; 
     lunch omni_markw-eng; 
     mka recoveryimage
```
