# yaml-slide-template

## Build Instructions

1. `git clone https://github.com/sivel/yaml-slide-template.git`
1. `cd yaml-slide-template`
1. Update root.yml with correct header information
1. Add chapters as standalone presentations
1. `git clone https://github.com/mpdehaan/revelator.git`
1. `python build_single.py > whatever.yml`
1. `cd revelator`
1. `./write_it ../whatever.yml whatever/`
1. Open whatever/index.html in your browser

### Dependencies

* PyYAML
