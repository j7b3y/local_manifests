```bash
repo init -u https://github.com/ProjectBlaze/manifest -b 14-QPR3 --git-lfs
git clone https://github.com/j7b3y/blaze_manifests .repo/local_manifests -b 14-QPR3
repo sync -c --force-sync --optimized-fetch --no-tags --no-clone-bundle --prune
```