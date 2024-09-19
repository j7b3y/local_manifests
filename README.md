```bash
repo init -u https://github.com/ProjectBlaze/manifest -b 14 --git-lfs
git clone https://github.com/j7b3y/blaze_manifests .repo/local_manifests -b blaze-3.x
repo sync -c --force-sync --optimized-fetch --no-tags --no-clone-bundle --prune
```
