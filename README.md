## 1. Toolchain setup
```
$ wget https://github.com/steward-fu/miyoo/releases/download/v1.0/toolchain.7z
$ 7za x toolchain.7z
$ sudo cp -a miyoo /opt/
$ source ./set-env.sh
```

## 2. Source code setup
```
$ git clone https://github.com/edemirkan/rg35xx-openbor.git
$ cd rg35xx-openbor
```

## 3. Compiling
```
$ make clean-all
$ make BUILD_RG35XX=1
```