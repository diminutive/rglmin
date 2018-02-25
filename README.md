[![Travis-CI Build Status](https://travis-ci.org/diminutive/rglmin.svg?branch=master)](https://travis-ci.org/diminutive/rglmin)

[![AppVeyor Build Status](https://ci.appveyor.com/api/projects/status/github/mdsumner/rglmin?branch=master&svg=true)](https://ci.appveyor.com/project/mdsumner/rglmin)


The bare minimum to import rgl and pass on Travis. 

The key thing as per `r help(rgl::rgl.useNULL)` is to put this in .travis.yml

```
before_install:
  - "export RGL_USE_NULL=TRUE
```

https://github.com/cran/rgl/blob/master/man/rgl.useNULL.Rd 
  
  
