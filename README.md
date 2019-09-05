## What is this?
This archive contains „app names“ for the appname-cache of
[Adebar](https://github.com/IzzySoft/Adebar) – for system apps which come
pre-installed on several devices. I've tried to apply a useful grouping, so
you have it easier to pick only the ones you need.


## How to use?
If you don't use *Adebar*, these files are probably not that useful to you. If
however you're already using *Adebar*, they will make your `sysApps.md` better
readable.

To install them, follow these steps:

* unpack the archive into an empty directory
* Adebar 1.6.0 and below:
    1. copy (or move) the files you think you'll need into *Adebar's* cache directory  
    2. simply remove what remains, you can always pick it from the archive lateron
* Adebar > 1.6.0:
    1. copy the files while keeping the directory structure (pick what matches your device(s)).
       Usually you will want to have the files directly from `sysApps/*` and the
       `sysApps/Android` folder. If you use Google apps, the `sysApps/Google` folder
       will be of interest. Additionally, pick the folder matching your device's
       vendor (if such folder does exist).
    2. simply remove what remains, you can always pick it from the archive lateron
    3. adjust the `APPCACHESPLUS` variable in your config to include the directories
       you've picked. It should e.g. read  
       `APPCACHESPLUS="sysApps sysApps/Android sysApps/Google"`  
       Note the names in this variable are relative to your `CACHEDIR/appnames`
       directory. Refer to the [directory settings](https://github.com/IzzySoft/Adebar/wiki/Configuration#directory-settings)
       in *Adebar's* wiki for reference on the configuration settings.

To figure where the cache directory is, check your config(s) for the `CACHEDIR`
variable. If that's not set, no cache is used – so you will first have to set it
up. Refer to the [corresponding Wiki page](https://github.com/IzzySoft/Adebar/wiki/Configuration)
for details.

Files/directories from this archive must go to `<cache>/appnames/`. That's it. On the
next run, *Adebar* will use them to display „human readable app names“ which
hopefully tell a little more on what each app is for.

The sub-directories in this archive are:

* `Android`: apps belonging to „stock Android“, so probably everyone will need these
* `BQ`: for devices of the Spanish manufacturer BQ
* `CM`: for users of CyanogenMod / LineageOS
* `CatSound`: apps are usually installed on tablets from *CatSound*
* `Google`: Unless you're running an [Android without Google](http://android.izzysoft.de/articles/named/android-without-google),
  these files are useful to you.
* `LG`: for LG devices
* `Lenovo`: for Lenovo tablets
* `MTK`: apps shipped on devices with MTK chipsets
* `Motorola`: apps specific to *Motorola* devices
* `QualComm`: apps shipped on devices with QualComm chips
* `Samsung`: the big ball of Samsung bloat (200+ picked from the S7 Edge, and I didn't find the rest)
* `Speadtrum`: apps by Speadtrum (Chinese chipset vendor)
* `Wiko:` for devices by the French manufacturer Wiko


## Further references
For further names, you can also refer to [What Android Apps(Bloatware) are Safe
to Remove? ](https://blog.burrowsapps.com/2014/03/what-android-apps-are-safe-to-remove.html)
