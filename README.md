### Quick Source Initialization ###
```bash
repo init -u https://github.com/iMOS-OSS/imos_manifest -b twelve-gsi
repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
