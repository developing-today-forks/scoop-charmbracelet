# use this now

- https://github.com/charmbracelet/scoop-bucket

```
scoop bucket add charmbracelet https://github.com/charmbracelet/scoop-bucket
```

# scoop-charmbracelet

A [Scoop](http://scoop.sh) bucket of useful [charmbracelet](https://github.com/charmbracelet/) utilities.

To make it easy to install apps from this bucket, run:

don't use this anymore!
```
scoop bucket add charmbracelet https://github.com/developing-today-forks/scoop-charmbracelet
```


## SHA check?

charmbracelet includes a `checksums.txt`, `checksums.txt.pem`, `checksums.txt.sig` files. These could be used to automatically check the hash of the downloaded file. As-is, we are not validating the hash and are relying on the github release being valid.


## Why does this exist?

For an app to be acceptable for the main bucket, it should be:

* open source
* a command-line program
* the latest stable version of the program
* reasonably well-known and widely used

The "extras" bucket has more relaxed requirements, so it's a good place to put anything that doesn't quite fit in the main bucket.

The "charmbracelet" bucket is specifically for the many utilities found on the charmbracelet website which haven't made it into the main bucket, _yet_.
