
### How to build:
First of all [clone LineageOS repo](https://github.com/LineageOS/android/tree/cm-14.1)

Then clone this local manifest

```cd $working_dir && git clone -b LineageOS-14.1 https://github.com/ALGPHELLO/local_manifests.git -b LineageOS-14.1 .repo/local_manifests && repo sync --force-sync```

### Once synced:

* cd $working_dir
* Aply Patch
* breakfast gnsz6753_66_n
* brunch gnsz6753_66_n
