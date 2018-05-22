# ocssw
a quick attempt to travis-CI-ify oceancolor's build process

## pre-reqs:
* git 1.7.3+ (for `-B` switch)

## install methods tested
Different methods of install are tested on different branches of this repo:

* script : installation using `install_ocssw.py`. refs:
    * [.../InstallOCSSW](https://seadas.gsfc.nasa.gov/help/seadas-processing/InstallOCSSW.html)
* repos  : installation using git repos directly. refs:
    * [/ocssw/](https://oceandata.sci.gsfc.nasa.gov/ocssw/)
* src    : build from source. refs:
    * [/docs/ocssw/](https://oceancolor.gsfc.nasa.gov/docs/ocssw/index.html)
    * [/build_ocssw/](https://seadas.gsfc.nasa.gov/build_ocssw/)

## tests
Tests used to evaluate successful install or build:
* [benchmark package](https://seadas.gsfc.nasa.gov/build_ocssw/#test-the-shiny-new-binraries)
>>>>>>> master
