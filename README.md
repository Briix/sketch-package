# sketch-package
Batch script for packing/unpacking sketch files for better use with version
control systems.

## Installation
Clone or download this repository and place `sketch-package` file in a
directory on your `PATH`.

```
$ git clone https://github.com/Briix/sketch-package
$ cd sketch-package
$ mv sketch-package /usr/local/bin
```

`/usr/local/bin` might not work for you, so check beforehand if it exists in
your `PATH`.

## Usage
Pass `sketch-package` either a directory you want to turn into a sketch file or
a sketch file you want to unpack.

```
$ sketch-package dir-or-sketch-file
```

Note: `sketch-package` will not check if the passed directory or sketch file
are valid.

## License
MIT
