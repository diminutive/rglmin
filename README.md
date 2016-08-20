## Bare minimum to Import rgl and pass on Travis

The key thing is to put this in .travis.yml

```
before_install:
  - "export RGL_USE_NULL=TRUE
```

As per

```R
?rgl::rgl.useNULL
```
https://github.com/cran/rgl/blob/master/man/rgl.useNULL.Rd 
  
  
[![Travis-CI Build Status](https://travis-ci.org/mdsumner/rglmin.svg?branch=master)](https://travis-ci.org/mdsumner/rglmin)

[![AppVeyor Build Status](https://ci.appveyor.com/api/projects/status/github/mdsumner/rglmin?branch=master&svg=true)](https://ci.appveyor.com/project/mdsumner/rglmin)

