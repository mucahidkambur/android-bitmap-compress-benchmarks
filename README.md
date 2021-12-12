## This repository contains examples of Bitmap.compress benchmarks

### The code that I used
```sh
bitmap.compress(Bitmap.CompressFormat.JPEG, quality, outputStream)
```


### Benchmarks

#### [Outside][0]
* Original: **6,00 MB**
* 100 quality: **9,14 MB**
* 80 quality: **2,76 MB**
* 60 quality: **1,86 MB**
* 40 quality: **1,43 MB**
* 20 quality: **967 KB**
* 0 quality: **175 KB**

#### [Object][1]
* Original: **3,61 MB**
* 100 quality: **7,54 MB**
* 80 quality: **1,46 MB**
* 60 quality: **923 KB**
* 40 quality: **674 KB**
* 20 quality: **422 KB**
* 0 quality: **120 KB**


[0]: https://github.com/mucahidkambur/android-bitmap-compress-benchmarks/tree/master/outside
[1]: https://github.com/mucahidkambur/android-bitmap-compress-benchmarks/tree/master/object
