TextGlass Varnish Client
========================

Requires Varnish Cache 4.1

HOWTO
-----

Update these 2 variables in src/Makefile:

```
VARNISH_PREFIX
TEXTGLASS_PREFIX
```

`VARNISH_PREFIX` is the prefix location where Varnish Cache 4.1 is installed.
`TEXTGLASS_PREFIX` is the location of the src folder for the TextGlass c client.

To compile, test, and install:

```
make
make test
make install
```
