<p align="center">
  <img src="PixelBlaster.png" />
</p>  

Credits:
=======
 * [**AOSP**](https://android.googlesource.com)
 * [**CAF**](https://source.codeaurora.org/)
 * [**Paranoid Android**](https://github.com/AOSPA)
 * [**LineageOS**](https://github.com/LineageOS)

### Getting Started: ###

To initialize your local repository, use the command:

```bash
repo init -u https://github.com/PixelBlaster-CAF/manifest -b 13
```

Then to download the entire source code use the command:

```bash
repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
```

### Building ###

The bundled builder tool `./rom-build.sh` handles all the building steps for the specified device
automatically. As the device value, you just feed it with the device codename.

```bash
$ ./rom-build.sh DEVICE
```

### Submitting Patches ###

Patches are always welcome! Fork any of the repos and make pull requests. Maintain Proper Authorship if picking someone else's commits.

### Apply for Official Maintainership ###

You can apply for officialy maintaining the ROM for your device by filling the form below.

https://forms.gle/7GJucJaVJmWeszfV9

After filling the form, contact @TheTablaster on telegram for further details.