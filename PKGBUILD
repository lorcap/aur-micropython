# Maintainer: Aman Gupta <aman.iv0012@gmail.com>
# Contributor: Lorenzo Cappelletti <lorenzo.cappelletti@gmail.com>
#
#
# In order to build one or more board firmware images:
#
# 1. uncomment the lines in `pkgname`
# 2. install packages from DEPENDENCIES column
# 3. run `makepkg --noextract --force`
#
# Not all boards are equally well supported. Feel free to contribute!

pkgbase=micropython
pkgname=(                                      # DEPENDENCIES
  'micropython'

  # 'micropython-port-barearm'                 # arm-none-eabi-gcc

  # 'micropython-port-cc3200'                  # arm-none-eabi-gcc

  # 'micropython-port-embed'

  # 'micropython-port-esp32-arduino'           # esp-idf
  # 'micropython-port-esp32-generic'           # esp-idf
  # 'micropython-port-esp32-liligo'            # esp-idf
  # 'micropython-port-esp32-lolin'             # esp-idf
  # 'micropython-port-esp32-m5stack'           # esp-idf
  # 'micropython-port-esp32-olimex'            # esp-idf
  # 'micropython-port-esp32-sil'               # esp-idf
  # 'micropython-port-esp32-umfeather'         # esp-idf
  # 'micropython-port-esp32-umtiny'            # esp-idf
  # 'micropython-port-esp32-umextra'           # esp-idf

  # 'micropython-port-esp8266'                 # docker

  # 'micropython-port-mimxrt-adafruit'         # arm-none-eabi-gcc
  # 'micropython-port-mimxrt-mimxrt101x'       # arm-none-eabi-gcc
  # 'micropython-port-mimxrt-mimxrt102x'       # arm-none-eabi-gcc
  # 'micropython-port-mimxrt-mimxrt105x'       # arm-none-eabi-gcc
  # 'micropython-port-mimxrt-mimxrt106x'       # arm-none-eabi-gcc
  # 'micropython-port-mimxrt-mimxrt107x'       # arm-none-eabi-gcc
  # 'micropython-port-mimxrt-olimex'           # arm-none-eabi-gcc
  # 'micropython-port-mimxrt-seeed'            # arm-none-eabi-gcc
  # 'micropython-port-mimxrt-teensy'           # arm-none-eabi-gcc

  # 'micropython-port-minimal'                 # arm-none-eabi-gcc

  # 'micropython-port-nrf-actinius'            # arm-none-eabi-gcc wget
  # 'micropython-port-nrf-arduino'             # arm-none-eabi-gcc wget
  # 'micropython-port-nrf-blueio'              # arm-none-eabi-gcc wget
  # 'micropython-port-nrf-dvk'                 # arm-none-eabi-gcc wget
  # 'micropython-port-nrf-evk'                 # arm-none-eabi-gcc wget
  # 'micropython-port-nrf-feather'             # arm-none-eabi-gcc wget
  # 'micropython-port-nrf-ibk'                 # arm-none-eabi-gcc wget
  # 'micropython-port-nrf-idk'                 # arm-none-eabi-gcc wget
  # 'micropython-port-nrf-microbit'            # arm-none-eabi-gcc wget
  # 'micropython-port-nrf-nrf52840'            # arm-none-eabi-gcc wget
  # 'micropython-port-nrf-particle'            # arm-none-eabi-gcc wget
  # 'micropython-port-nrf-pca1000x'            # arm-none-eabi-gcc wget
  # 'micropython-port-nrf-pca1002x'            # arm-none-eabi-gcc wget
  # 'micropython-port-nrf-pca1003x'            # arm-none-eabi-gcc wget
  # 'micropython-port-nrf-pca1004x'            # arm-none-eabi-gcc wget
  # 'micropython-port-nrf-pca1005x'            # arm-none-eabi-gcc wget
  # 'micropython-port-nrf-pca1009x'            # arm-none-eabi-gcc wget
  # 'micropython-port-nrf-seeed'               # arm-none-eabi-gcc wget
  # 'micropython-port-nrf-wt'                  # arm-none-eabi-gcc wget

  # 'micropython-port-pic16bit'

  # 'micropython-port-powerpc'

  # 'micropython-port-qemu-microbit'           # arm-none-eabi-gcc
  # 'micropython-port-qemu-mbs2'               # arm-none-eabi-gcc
  # 'micropython-port-qemu-netduino'           # arm-none-eabi-gcc
  # 'micropython-port-qemu-sabrelite'          # arm-none-eabi-gcc
  # 'micropython-port-qemu-virt'               # riscv64-unknown-elf-gcc

  # 'micropython-port-renesas-arduino'         # arm-none-eabi-gcc
  # 'micropython-port-renesas-ek4'             # arm-none-eabi-gcc
  # 'micropython-port-renesas-ek6'             # arm-none-eabi-gcc
  # 'micropython-port-renesas-ra'              # arm-none-eabi-gcc
  # 'micropython-port-renesas-vk'              # arm-none-eabi-gcc

  # 'micropython-port-rp2-adafruit'            # picotool cmake
  # 'micropython-port-rp2-arduino'             # picotool cmake
  # 'micropython-port-rp2-garatronic'          # picotool cmake
  # 'micropython-port-rp2-nullbits'            # picotool cmake
  # 'micropython-port-rp2-pimoroni'            # picotool cmake
  # 'micropython-port-rp2-pololu'              # picotool cmake
  # 'micropython-port-rp2-rpi'                 # picotool cmake
  # 'micropython-port-rp2-sil'                 # picotool cmake
  # 'micropython-port-rp2-sparkfun'            # picotool cmake
  # 'micropython-port-rp2-w5xxx'               # picotool cmake
  # 'micropython-port-rp2-weact'               # picotool cmake

  # 'micropython-port-samd-adafruitfeather'    # arm-none-eabi-gcc
  # 'micropython-port-samd-adafruittsybitsy'   # arm-none-eabi-gcc
  # 'micropython-port-samd-samd'               # arm-none-eabi-gcc
  # 'micropython-port-samd-adafruittrinket'    # arm-none-eabi-gcc
  # 'micropython-port-samd-minisam'            # arm-none-eabi-gcc
  # 'micropython-port-samd-samd2'              # arm-none-eabi-gcc
  # 'micropython-port-samd-seeed'              # arm-none-eabi-gcc
  # 'micropython-port-samd-sparkfun'           # arm-none-eabi-gcc

  # 'micropython-port-stm32-adafruit'          # arm-none-eabi-gcc
  # 'micropython-port-stm32-b'                 # arm-none-eabi-gcc
  # 'micropython-port-stm32-cerb'              # arm-none-eabi-gcc
  # 'micropython-port-stm32-espruino'          # arm-none-eabi-gcc
  # 'micropython-port-stm32-garatronic'        # arm-none-eabi-gcc
  # 'micropython-port-stm32-hydrabus'          # arm-none-eabi-gcc
  # 'micropython-port-stm32-lego'              # arm-none-eabi-gcc
  # 'micropython-port-stm32-limifrog'          # arm-none-eabi-gcc
  # 'micropython-port-stm32-mikroe'            # arm-none-eabi-gcc
  # 'micropython-port-stm32-netduino'          # arm-none-eabi-gcc
  # 'micropython-port-stm32-nucleof0'          # arm-none-eabi-gcc
  # 'micropython-port-stm32-nucleof4'          # arm-none-eabi-gcc
  # 'micropython-port-stm32-nucleof7'          # arm-none-eabi-gcc
  # 'micropython-port-stm32-nucleog'           # arm-none-eabi-gcc
  # 'micropython-port-stm32-nucleoh'           # arm-none-eabi-gcc
  # 'micropython-port-stm32-nucleol'           # arm-none-eabi-gcc
  # 'micropython-port-stm32-nucleow'           # arm-none-eabi-gcc
  # 'micropython-port-stm32-olimex'            # arm-none-eabi-gcc
  # 'micropython-port-stm32-pybd'              # arm-none-eabi-gcc
  # 'micropython-port-stm32-pyblite'           # arm-none-eabi-gcc
  # 'micropython-port-stm32-pybv'              # arm-none-eabi-gcc
  # 'micropython-port-stm32-sparkfun'          # arm-none-eabi-gcc
  # 'micropython-port-stm32-stm32f4'           # arm-none-eabi-gcc
  # 'micropython-port-stm32-stm32f7'           # arm-none-eabi-gcc
  # 'micropython-port-stm32-stm32h'            # arm-none-eabi-gcc
  # 'micropython-port-stm32-stm32l'            # arm-none-eabi-gcc
  # 'micropython-port-stm32-usbdongle'         # arm-none-eabi-gcc
  # 'micropython-port-stm32-vccgnd'            # arm-none-eabi-gcc

  # 'micropython-port-zephyr'                  # zephyr-sdk?
)
pkgver=1.24.1
_libver=1.24.1
pkgrel=1
pkgdesc='A Python implementation for microcontrollers'
arch=('x86_64')
url="http://micropython.org/"
changelog='ChangeLog'
license=('MIT')
options=('!debug' '!emptydirs')
makedepends=(
  # micropython
  'gcc'

  # mpremote
  'python'
  'python-hatchling'
  'python-hatch-requirements-txt'
  'python-installer'
  'python-pyserial'

  # most boards
  # 'arm-none-eabi-gcc' 'arm-none-eabi-newlib'

  # NRF boards
  # 'wget'

  # rp2 boards
  # 'cmake' 'picotool'

  # other boards
  # 'riscv64-unknown-elf-gcc'
)
source=(
  "https://micropython.org/resources/source/micropython-$pkgver.tar.xz"
  "tools-mpremote-pyproject.toml.patch")
sha256sums=('5d624a0b23389134d963b204601db9bc4ca57bfb615d13f13592bc2b5b494c03'
          '54fbda3578ed9519906e54912aa4358bbfb5f4aadbcf08906d48892c22c1dd47')

prepare() {
  cd $pkgbase-$pkgver
  for patch in tools-mpremote-pyproject.toml.patch
  do
    sed -e s/'\${pkgver}'/"$pkgver"/ < ../$patch | patch -Np1
  done
  cd - > /dev/null

  mpy-cross prepare
  mpremote prepare
  port-unix prepare
  port-minimal-host prepare

  local port board
  for name in ${pkgname[@]}; do
    board=${name#micropython-port-}
    [[ $name = $board ]] && continue
    port=${board%-*}
    port-$port prepare
  done

  [[ $port ]] || echo -e "${YELLOW}
*****************************************************************
Micropython binaries for Linux are built by default. If you need
to work with board firmware images, customize this PKGBUILD at:
$startdir/PKGBUILD
*****************************************************************
${ALL_OFF}"
}

build() {
  export MAKEFLAGS=BUILD_VERBOSE=0 $MAKEFLAGS
  mpy-cross build
  mpremote build
  port-unix build
  port-minimal-host build

  export -n CPPFLAGS CFLAGS CXXFLAGS LDFLAGS LTOFLAGS
  local port board
  for name in ${pkgname[@]}; do
    board=${name#micropython-port-}
    [[ $name = $board ]] && continue
    port=${board%-*}
    port-$port build "${BOARDS[$board]}"
  done
}

check() {
  make -C $pkgbase-$pkgver/ports/unix test
}

package_micropython() {
  pkgdesc='A Python implementation for microcontrollers (host)'
  depends=('readline' 'libffi')
  conflicts=('mpy-cross' 'mpcross')

  mpy-cross pack
  mpremote pack
  port-unix pack
  port-minimal-host pack

  cd $pkgbase-$pkgver
  install -Dm644 LICENSE $pkgdir/usr/share/licenses/$pkgbase/LICENSE
  cd - > /dev/null
}

# bare-arm
package_micropython-port-barearm() {
  port-barearm pack "${BOARDS[barearm]}"
}

# embed
package_micropython-port-embed() {
  port-embed pack "${BOARDS[embed]}"
}

# CC3200
package_micropython-port-cc3200() {
  port-cc3200 pack "${BOARDS[cc3200]}"
}

# ESP32
package_micropython-port-esp32-arduino() {
  port-esp32 pack "${BOARDS[esp32-arduino]}"
}
package_micropython-port-esp32-generic() {
  port-esp32 "${BOARDS[esp32-generic]}"
}
package_micropython-port-esp32-liligo() {
  port-esp32 "${BOARDS[esp32-liligo]}"
}
package_micropython-port-esp32-lolin() {
  port-esp32 "${BOARDS[esp32-lolin]}"
}
package_micropython-port-esp32-m5stack() {
  port-esp32 "${BOARDS[esp32-m5stack]}"
}
package_micropython-port-esp32-olimex() {
  port-esp32 "${BOARDS[esp32-olimex]}"
}
package_micropython-port-esp32-sil() {
  port-esp32 "${BOARDS[esp32-sil]}"
}
package_micropython-port-esp32-umfeather() {
  port-esp32 "${BOARDS[esp32-umfeather]}"
}
package_micropython-port-esp32-umtiny() {
  port-esp32 "${BOARDS[esp32-umtiny]}"
}
package_micropython-port-esp32-umextra() {
  port-esp32 "${BOARDS[esp32-umextra]}"
}

# ESP8266
package_micropython-port-esp8266() {
  port-esp8266 pack "${BOARDS[esp8266]}"
}

# minimal
package_micropython-port-minimal() {
  port-minimal pack "${BOARDS[minimal]}"
}

# MIMXRT
package_micropython-port-mimxrt-adafruit() {
  port-mimxrt pack "${BOARDS[mimxrt-adafruit]}"
}
package_micropython-port-mimxrt-mimxrt101x() {
  port-mimxrt pack "${BOARDS[mimxrt-mimxrt101x]}"
}
package_micropython-port-mimxrt-mimxrt102x() {
  port-mimxrt pack "${BOARDS[mimxrt-mimxrt102x]}"
}
package_micropython-port-mimxrt-mimxrt105x() {
  port-mimxrt pack "${BOARDS[mimxrt-mimxrt105x]}"
}
package_micropython-port-mimxrt-mimxrt106x() {
  port-mimxrt pack "${BOARDS[mimxrt-mimxrt106x]}"
}
package_micropython-port-mimxrt-mimxrt107x() {
  port-mimxrt pack "${BOARDS[mimxrt-mimxrt107x]}"
}
package_micropython-port-mimxrt-olimex() {
  port-mimxrt pack "${BOARDS[mimxrt-olimex]}"
}
package_micropython-port-mimxrt-seeed() {
  port-mimxrt pack "${BOARDS[mimxrt-seeed]}"
}
package_micropython-port-mimxrt-teensy() {
  port-mimxrt pack "${BOARDS[mimxrt-teensy]}"
}

# NRF
package_micropython-port-nrf-actinius() {
  port-nrf pack "${BOARDS[nrf-actinius]}"
}
package_micropython-port-nrf-arduino() {
  port-nrf pack "${BOARDS[nrf-arduino]}"
}
package_micropython-port-nrf-blueio() {
  port-nrf pack "${BOARDS[nrf-blueio]}"
}
package_micropython-port-nrf-dvk() {
  port-nrf pack "${BOARDS[nrf-dvk]}"
}
package_micropython-port-nrf-evk() {
  port-nrf pack "${BOARDS[nrf-evk]}"
}
package_micropython-port-nrf-feather() {
  port-nrf pack "${BOARDS[nrf-feather]}"
}
package_micropython-port-nrf-ibk() {
  port-nrf pack "${BOARDS[nrf-ibk]}"
}
package_micropython-port-nrf-idk() {
  port-nrf pack "${BOARDS[nrf-idk]}"
}
package_micropython-port-nrf-microbit() {
  port-nrf pack "${BOARDS[nrf-microbit]}"
}
package_micropython-port-nrf-nrf52840() {
  port-nrf pack "${BOARDS[nrf-nrf52840]}"
}
package_micropython-port-nrf-particle() {
  port-nrf pack "${BOARDS[nrf-particle]}"
}
package_micropython-port-nrf-pca1000x() {
  port-nrf pack "${BOARDS[nrf-pca1000x]}"
}
package_micropython-port-nrf-pca1002x() {
  port-nrf pack "${BOARDS[nrf-pca1002x]}"
}
package_micropython-port-nrf-pca1003x() {
  port-nrf pack "${BOARDS[nrf-pca1003x]}"
}
package_micropython-port-nrf-pca1004x() {
  port-nrf pack "${BOARDS[nrf-pca1004x]}"
}
package_micropython-port-nrf-pca1005x() {
  port-nrf pack "${BOARDS[nrf-pca1005x]}"
}
package_micropython-port-nrf-pca1009x() {
  port-nrf pack "${BOARDS[nrf-pca1009x]}"
}
package_micropython-port-nrf-seeed() {
  port-nrf pack "${BOARDS[nrf-seeed]}"
}
package_micropython-port-nrf-wt() {
  port-nrf pack "${BOARDS[nrf-wt]}"
}

# pic16bit
package_micropython-port-pic16bit() {
  port-pic16bit pack "${BOARDS[pic16bit]}"
}

# powerpc
package_micropython-port-powerpc() {
  port-poewrpc pack "${BOARDS[powerpc]}"
}

# qemu
package_micropython-port-qemu-microbit() {
  port-qemu pack "${BOARDS[qemu-microbit]}"
}
package_micropython-port-qemu-mbs2() {
  port-qemu pack "${BOARDS[qemu-mbs2]}"
}
package_micropython-port-qemu-netduino() {
  port-qemu pack "${BOARDS[qemu-netduino]}"
}
package_micropython-port-qemu-sabrelite() {
  port-qemu pack "${BOARDS[qemu-sabrelite]}"
}
package_micropython-port-qemu-virt() {
  port-qemu pack "${BOARDS[qemu-virt]}"
}

# renesas-ra
package_micropython-port-renesas-arduino() {
  port-renesas pack "${BOARDS[renesas-arduino]}"
}
package_micropython-port-renesas-ek4() {
  port-renesas pack "${BOARDS[renesas-ek4]}"
}
package_micropython-port-renesas-ek6() {
  port-renesas pack "${BOARDS[renesas-ek6]}"
}
package_micropython-port-renesas-ra() {
  port-renesas pack "${BOARDS[renesas-ra]}"
}
package_micropython-port-renesas-vk() {
  port-renesas pack "${BOARDS[renesas-vk]}"
}

# RP2
package_micropython-port-rp2-adafruit() {
  port-rp2 pack "${BOARDS[rp2-adafruit]}"
}
package_package_micropython-port-renesas-vk() {
  port-rp2 pack "${BOARDS[rp2-vk]}"
}
package_micropython-port-rp2-arduino() {
  port-rp2 pack "${BOARDS[rp2-arduino]}"
}
package_micropython-port-rp2-garatronic() {
  port-rp2 pack "${BOARDS[rp2-garatronic]}"
}
package_micropython-port-rp2-nullbits() {
  port-rp2 pack "${BOARDS[rp2-nullbits]}"
}
package_micropython-port-rp2-pimoroni() {
  port-rp2 pack "${BOARDS[rp2-pimoroni]}"
}
package_micropython-port-rp2-pololu() {
  port-rp2 pack "${BOARDS[rp2-pololu]}"
}
package_micropython-port-rp2-rpi() {
  port-rp2 pack "${BOARDS[rp2-rpi]}"
}
package_micropython-port-rp2-sil() {
  port-rp2 pack "${BOARDS[rp2-sil]}"
}
package_micropython-port-rp2-sparkfun() {
  port-rp2 pack "${BOARDS[rp2-sparkfun]}"
}
package_micropython-port-rp2-w5xxx() {
  port-rp2 pack "${BOARDS[rp2-w5xxx]}"
}
package_micropython-port-rp2-weact() {
  port-rp2 pack "${BOARDS[rp2-weact]}"
}

# SAMD
package_micropython-port-samd-adafruitfeather() {
  port-samd pack "${BOARDS[samd-adafruitfeather]}"
}
package_micropython-port-samd-adafruittsybitsy() {
  port-samd pack "${BOARDS[samd-adafruittsybitsy]}"
}
package_micropython-port-samd-samd() {
  port-samd pack "${BOARDS[samd-samd]}"
}
package_micropython-port-samd-adafruittrinket() {
  port-samd pack "${BOARDS[samd-adafruittrinket]}"
}
package_micropython-port-samd-minisam() {
  port-samd pack "${BOARDS[samd-minisam]}"
}
package_micropython-port-samd-samd2() {
  port-samd pack "${BOARDS[samd-samd2]}"
}
package_micropython-port-samd-seeed() {
  port-samd pack "${BOARDS[samd-seeed]}"
}
package_micropython-port-samd-sparkfun() {
  port-samd pack "${BOARDS[samd-sparkfun]}"
}

# STM32
package_micropython-port-stm32-adafruit() {
  port-stm32 pack "${BOARDS[stm32-adafruit]}"
}
package_micropython-port-stm32-b() {
  port-stm32 pack "${BOARDS[stm32-b]}"
}
package_micropython-port-stm32-cerb() {
  port-stm32 pack "${BOARDS[stm32-cerb]}"
}
package_micropython-port-stm32-espruino() {
  port-stm32 pack "${BOARDS[stm32-espruino]}"
}
package_micropython-port-stm32-garatronic() {
  port-stm32 pack "${BOARDS[stm32-garatronic]}"
}
package_micropython-port-stm32-hydrabus() {
  port-stm32 pack "${BOARDS[stm32-hydrabus]}"
}
package_micropython-port-stm32-lego() {
  port-stm32 pack "${BOARDS[stm32-lego]}"
}
package_micropython-port-stm32-limifrog() {
  port-stm32 pack "${BOARDS[stm32-limifrog]}"
}
package_micropython-port-stm32-mikroe() {
  port-stm32 pack "${BOARDS[stm32-mikroe]}"
}
package_micropython-port-stm32-netduino() {
  port-stm32 pack "${BOARDS[stm32-netduino]}"
}
package_micropython-port-stm32-nucleof0() {
  port-stm32 pack "${BOARDS[stm32-nucleof0]}"
}
package_micropython-port-stm32-nucleof4() {
  port-stm32 pack "${BOARDS[stm32-nucleof4]}"
}
package_micropython-port-stm32-nucleof7() {
  port-stm32 pack "${BOARDS[stm32-nucleof7]}"
}
package_micropython-port-stm32-nucleog() {
  port-stm32 pack "${BOARDS[stm32-nucleog]}"
}
package_micropython-port-stm32-nucleoh() {
  port-stm32 pack "${BOARDS[stm32-nucleoh]}"
}
package_micropython-port-stm32-nucleol() {
  port-stm32 pack "${BOARDS[stm32-nucleol]}"
}
package_micropython-port-stm32-nucleow() {
  port-stm32 pack "${BOARDS[stm32-nucleow]}"
}
package_micropython-port-stm32-olimex() {
  port-stm32 pack "${BOARDS[stm32-olimex]}"
}
package_micropython-port-stm32-pybd() {
  port-stm32 pack "${BOARDS[stm32-pybd]}"
}
package_micropython-port-stm32-pyblite() {
  port-stm32 pack "${BOARDS[stm32-pyblite]}"
}
package_micropython-port-stm32-pybv() {
  port-stm32 pack "${BOARDS[stm32-pybv]}"
}
package_micropython-port-stm32-sparkfun() {
  port-stm32 pack "${BOARDS[stm32-sparkfun]}"
}
package_micropython-port-stm32-stm32f4() {
  port-stm32 pack "${BOARDS[stm32-stm32f4]}"
}
package_micropython-port-stm32-stm32f7() {
  port-stm32 pack "${BOARDS[stm32-stm32f7]}"
}
package_micropython-port-stm32-stm32h() {
  port-stm32 pack "${BOARDS[stm32-stm32h]}"
}
package_micropython-port-stm32-stm32l() {
  port-stm32 pack "${BOARDS[stm32-stm32l]}"
}
package_micropython-port-stm32-usbdongle() {
  port-stm32 pack "${BOARDS[stm32-usbdongle]}"
}
package_micropython-port-stm32-vccgnd() {
  port-stm32 pack "${BOARDS[stm32-vccgnd]}"
}

# zephyr
package_micropython-port-zephyr() {
  port-zephyr pack "${BOARDS[zephyr]}"
}


### helper functions ########################################################

declare -gA BOARDS=(
  ['barearm']=''

  ['embed']=''

  ['cc3200']='LAUNCHXL WIPY'

  ['esp32-arduino']='ARDUINO_NANO_ESP32'
  ['esp32-generic']='ESP32_GENERIC ESP32_GENERIC_C3 ESP32_GENERIC_C6 ESP32_GENERIC_S2 ESP32_GENERIC_S3'
  ['esp32-liligo']='LILYGO_TTGO_LORA32'
  ['esp32-lolin']='LOLIN_C3_MINI LOLIN_S2_MINI LOLIN_S2_PICO'
  ['esp32-m5stack']='M5STACK_ATOM M5STACK_ATOMS3_LITE M5STACK_NANOC6'
  ['esp32-olimex']='OLIMEX_ESP32_EVB OLIMEX_ESP32_POE'
  ['esp32-sil']='SIL_WESP32'
  ['esp32-umfeather']='UM_FEATHERS2 UM_FEATHERS2NEO UM_FEATHERS3 UM_FEATHERS3NEO'
  ['esp32-umtiny']='UM_TINYC6 UM_TINYPICO UM_TINYS2 UM_TINYS3 UM_TINYWATCHS3'
  ['esp32-umextra']='UM_NANOS3 UM_OMGS3 UM_PROS3 UM_RGBTOUCH_MINI'

  ['esp8266']='ESP8266_GENERIC'

  ['minimal']=''

  ['mimxrt-adafruit']='ADAFRUIT_METRO_M7'
  ['mimxrt-mimxrt101x']='MIMXRT1010_EVK MIMXRT1015_EVK'
  ['mimxrt-mimxrt102x']='MIMXRT1020_EVK'
  ['mimxrt-mimxrt105x']='MIMXRT1050_EVK'
  ['mimxrt-mimxrt106x']='MIMXRT1060_EVK MIMXRT1064_EVK'
  ['mimxrt-mimxrt107x']='MIMXRT1170_EVK'
  ['mimxrt-olimex']='OLIMEX_RT1010'
  ['mimxrt-seeed']='SEEED_ARCH_MIX'
  ['mimxrt-teensy']='TEENSY40 TEENSY41'

  ['nrf-actinius']='ACTINIUS_ICARUS'
  ['nrf-arduino']='ARDUINO_NANO_33_BLE_SENSE ARDUINO_PRIMO'
  ['nrf-blueio']='BLUEIO_TAG_EVIM'
  ['nrf-dvk']='DVK_BL652'
  ['nrf-evk']='EVK_NINA_B1 EVK_NINA_B3'
  ['nrf-feather']='FEATHER52'
  ['nrf-ibk']='IBK_BLYST_NANO'
  ['nrf-idk']='IDK_BLYST_NANO'
  ['nrf-microbit']='MICROBIT'
  ['nrf-nrf52840']='NRF52840_MDK_USB_DONGLE'
  ['nrf-particle']='PARTICLE_XENON'
  ['nrf-pca1000x']='PCA10000 PCA10001'
  ['nrf-pca1002x']='PCA10028'
  ['nrf-pca1003x']='PCA10031'
  ['nrf-pca1004x']='PCA10040'
  ['nrf-pca1005x']='PCA10056 PCA10059'
  ['nrf-pca1009x']='PCA10090'
  ['nrf-seeed']='SEEED_XIAO_NRF52'
  ['nrf-wt']='WT51822_S4AT'

  ['pic16bit']=''

  ['powerpc']=''

  ['qemu-microbit']='MICROBIT'
  ['qemu-mbs2']='MPS2_AN385'
  ['qemu-netduino']='NETDUINO2'
  ['qemu-sabrelite']='SABRELITE'
  ['qemu-virt']='VIRT_RV32'

  ['renesas-arduino']='ARDUINO_PORTENTA_C33'
  ['renesas-ek4']='EK_RA4M1 EK_RA4W1'
  ['renesas-ek6']='EK_RA6M1 EK_RA6M2'
  ['renesas-ra']='RA4M1_CLICKER'
  ['renesas-vk']='VK_RA6M5'

  ['rp2-adafruit']='ADAFRUIT_FEATHER_RP2040 ADAFRUIT_ITSYBITSY_RP2040 ADAFRUIT_QTPY_RP2040'
  ['rp2-arduino']='ARDUINO_NANO_RP2040_CONNECT'
  ['rp2-garatronic']='GARATRONIC_PYBSTICK26_RP2040'
  ['rp2-nullbits']='NULLBITS_BIT_C_PRO'
  ['rp2-pimoroni']='PIMORONI_PICOLIPO PIMORONI_TINY2040'
  ['rp2-pololu']='POLOLU_3PI_2040_ROBOT POLOLU_ZUMO_2040_ROBOT'
  ['rp2-rpi']='RPI_PICO RPI_PICO2 RPI_PICO_W'
  ['rp2-sil']='SIL_RP2040_SHIM'
  ['rp2-sparkfun']='SPARKFUN_PROMICRO SPARKFUN_THINGPLUS'
  ['rp2-w5xxx']='W5100S_EVB_PICO W5500_EVB_PICO'
  ['rp2-weact']='WEACTSTUDIO'

  ['samd-adafruitfeather']='ADAFRUIT_FEATHER_M0_EXPRESS ADAFRUIT_FEATHER_M4_EXPRESS'
  ['samd-adafruittsybitsy']='ADAFRUIT_ITSYBITSY_M0_EXPRESS ADAFRUIT_ITSYBITSY_M4_EXPRESS'
  ['samd'adafruitmetro]='ADAFRUIT_METRO_M4_EXPRESS'
  ['samd-adafruittrinket']='ADAFRUIT_TRINKET_M0'
  ['samd-minisam']='MINISAM_M4'
  ['samd-samd2']='SAMD21_XPLAINED_PRO'
  ['samd-seeed']='SEEED_WIO_TERMINAL SEEED_XIAO_SAMD21'
  ['samd-sparkfun']='SPARKFUN_SAMD51_THING_PLUS'

  ['stm32-adafruit']='ADAFRUIT_F405_EXPRESS ARDUINO_GIGA ARDUINO_NICLA_VISION ARDUINO_OPTA ARDUINO_PORTENTA_H7'
  ['stm32-b']='B_L072Z_LRWAN1 B_L475E_IOT01A'
  ['stm32-cerb']='CERB40'
  ['stm32-espruino']='ESPRUINO_PICO'
  ['stm32-garatronic']='GARATRONIC_NADHAT_F405 GARATRONIC_PYBSTICK26_F411'
  ['stm32-hydrabus']='HYDRABUS'
  ['stm32-lego']='LEGO_HUB_NO6 LEGO_HUB_NO7'
  ['stm32-limifrog']='LIMIFROG'
  ['stm32-mikroe']='MIKROE_CLICKER2_STM32 MIKROE_QUAIL'
  ['stm32-netduino']='NETDUINO_PLUS_2'
  ['stm32-nucleof0']='NUCLEO_F091RC'
  ['stm32-nucleof4']='NUCLEO_F401RE NUCLEO_F411RE NUCLEO_F412ZG NUCLEO_F413ZH NUCLEO_F429ZI NUCLEO_F439ZI NUCLEO_F446RE'
  ['stm32-nucleof7']='NUCLEO_F722ZE NUCLEO_F746ZG NUCLEO_F756ZG NUCLEO_F767ZI'
  ['stm32-nucleog']='NUCLEO_G0B1RE NUCLEO_G474RE'
  ['stm32-nucleoh']='NUCLEO_H563ZI NUCLEO_H723ZG NUCLEO_H743ZI NUCLEO_H743ZI2'
  ['stm32-nucleol']='NUCLEO_L073RZ NUCLEO_L152RE NUCLEO_L432KC NUCLEO_L452RE NUCLEO_L476RG NUCLEO_L4A6ZG'
  ['stm32-nucleow']='NUCLEO_WB55 NUCLEO_WL55'
  ['stm32-olimex']='OLIMEX_E407 OLIMEX_H407'
  ['stm32-pybd']='PYBD_SF2 PYBD_SF3 PYBD_SF6'
  ['stm32-pyblite']='PYBLITEV10'
  ['stm32-pybv']='PYBV10 PYBV11 PYBV3 PYBV4'
  ['stm32-sparkfun']='SPARKFUN_MICROMOD_STM32'
  ['stm32-stm32f4']='STM32F411DISC STM32F429DISC STM32F439 STM32F4DISC'
  ['stm32-stm32f7']='STM32F769DISC STM32F7DISC'
  ['stm32-stm32h']='STM32H573I_DK STM32H7B3I_DK'
  ['stm32-stm32l']='STM32L476DISC STM32L496GDISC'
  ['stm32-usbdongle']='USBDONGLE_WB55'
  ['stm32-vccgnd']='VCC_GND_F407VE VCC_GND_F407ZG VCC_GND_H743VI'

  ['zephyr']=''
)

echo_header() {
  echo -e "${BOLD}${GREEN}---> $1${ALL_OFF}"
}

mpremote() {
  cd $pkgbase-$pkgver/tools/mpremote
  local cmd=$1
  if [[ $1 = prepare ]]; then
    :
  else
    echo_header mpremote
    if [[ $1 = build ]]; then
      python -m build --wheel --no-isolation
    elif [[ $1 = pack ]]; then
      python -m installer --destdir=$pkgdir dist/*.whl
    fi
  fi
  cd - > /dev/null
}

mpy-cross() {
  cd $pkgbase-$pkgver/mpy-cross
  local cmd=$1
  if [[ $1 = prepare ]]; then
    :
  else
    echo_header mpy-cross
    if [[ $1 = build ]]; then
      make
    elif [[ $1 = pack ]]; then
      install -D build/mpy-cross "$pkgdir/usr/bin/mpy-cross"
    fi
  fi
  cd - > /dev/null
}

port-barearm() {
  cd $pkgbase-$pkgver/ports/bare-arm
  local cmd=$1
  if [[ $1 = prepare ]]; then
    :
  else
    echo_header bare-arm
    if [[ $1 = build ]]; then
      make
    elif [[ $1 = pack ]]; then
      pkgdesc="bare-minimum to get Micropython on a bare-metal ARM-based target"
      arch=('any')
      groups=('micropython-port')
      install -Dm644 -t $pkgdir/usr/share/$pkgbase/ports/bare-arm\
        README.md\
        build/firmware*
    fi
  fi
  cd - > /dev/null
}

port-cc3200() {
  cd $pkgbase-$pkgver/ports/cc3200
  local cmd=$1
  if [[ $cmd = prepare ]]; then
    :
  else
    local boards=$2
    local once
    for board in $boards; do
      echo_header cc3200/$board
      if [[ $cmd = build ]]; then
        make BTARGET=bootloader BTYPE=release BOARD=$board
        make BTARGET=application BTYPE=release BOARD=$board
      elif [[ $cmd = pack ]]; then
        install -Dm644 -t $pkgdir/usr/share/$pkgbase/ports/cc3200/$board\
          build/$board/release/firmware*
        if [[ ! $once ]]; then once=1
          pkgdesc="Port of Micropython to boards: $boards"
          groups=('micropython-port')
          arch=('any')
          options=('!strip')
          install -Dm644 -t $pkgdir/usr/share/$pkgbase/ports/cc3200 README.md
        fi
      fi
    done
  fi
  cd - > /dev/null
}

port-embed() {
  cd $pkgbase-$pkgver/ports/embed
  local cmd=$1
  if [[ $cmd = prepare ]]; then
    :
  else
    echo_header embed
    if [[ $cmd = build ]]; then
      :
    elif [[ $cmd = pack ]]; then
      pkgdesc="Set of C files for embedding Micropython into a wider project"
      arch=('any')
      groups=('micropython-port')
      install -Dm644 -t $pkgdir/usr/share/$pkgbase/ports/embed\
        embed.mk README.md
      install -Dm644 -t $pkgdir/usr/share/$pkgbase/ports/embed/port\
        port/*
    fi
  fi
  cd - > /dev/null
}

port-esp32() {
  # needs esp-idf
  cd $pkgbase-$pkgver/ports/esp32
  local cmd=$1
  if [[ $cmd = prepare ]]; then
    source /opt/esp-idf/export.sh
  else
    local boards=$2
    local once
    for board in $boards; do
      echo_header esp32/$board
      if [[ $cmd = build ]]; then
        make BOARD=$board
      elif [[ $cmd = pack ]]; then
        install -Dm644 -t $pkgdir/usr/share/$pkgbase/ports/esp32/$board\
          build-$board/firmware*
        if [[ ! $once ]]; then once=1
          pkgdesc="Port of Micropython to boards: $boards"
          groups=('micropython-port' 'micropython-port-esp32')
          options=('!strip')
          arch=('any')
          install -Dm644 -t $pkgdir/usr/share/$pkgbase/ports/esp32 README.md
        fi
      fi
    done
  fi
  cd - > /dev/null
}

port-esp8266() {
  # needs docker
  local binddir=$PWD/$pkgbase-$pkgver
  cd $pkgbase-$pkgver/ports/esp8266
  local mpycrossdir=../../mpy-cross
  local docker_run="docker run --rm -v $binddir:$binddir -u $UID -w $PWD larsks/esp-open-sdk"
  local cmd=$1
  if [[ $cmd = prepare ]]; then
    docker pull larsks/esp-open-sdk
  else
    local boards=$2
    local once
    for board in $boards; do
      echo_header esp8266/$board
      if [[ $cmd = build ]]; then
        $docker_run make -C $mpycrossdir BUILD_VERBOSE=0 BUILD=build-esp8266
        $docker_run make BUILD_VERBOSE=0 BOARD=$board\
            MICROPY_MPYCROSS=$mpycrossdir/build-esp8266/mpy-cross
      elif [[ $cmd = pack ]]; then
        install -Dm644 -t $pkgdir/usr/share/$pkgbase/ports/esp8266/$board\
          build-$board/firmware*
        if [[ ! $once ]]; then once=1
          pkgdesc="Port of Micropython to boards: $boards"
          groups=('micropython-port')
          options=('!strip')
          arch=('any')
          install -Dm644 -t $pkgdir/usr/share/$pkgbase/ports/esp8266 README.md
        fi
      fi
    done
  fi
  cd - > /dev/null
}

port-mimxrt() {
  cd $pkgbase-$pkgver/ports/mimxrt
  local cmd=$1
  if [[ $cmd = prepare ]]; then
    :
  else
    local boards=$2
    local once
    for board in $boards; do
      echo_header mimxrt/$board
      if [[ $cmd = build ]]; then
        make BOARD=$board
      elif [[ $cmd = pack ]]; then
        install -Dm644 -t $pkgdir/usr/share/$pkgbase/ports/mimxrt/$board\
          build-$board/firmware*
        [[ ! $once ]] && once=1 &&\
          install -Dm644 -t $pkgdir/usr/share/$pkgbase/ports/mimxrt README.md
      fi
    done
  fi
  cd - > /dev/null
}

port-minimal() {
  cd $pkgbase-$pkgver/ports/minimal
  local cmd=$1
  if [[ $cmd = prepare ]]; then
    :
  else
    echo_header minimal
    if [[ $cmd = build ]]; then
      make CROSS=1
    elif [[ $cmd = pack ]]; then
      install -Dm644 -t $pkgdir/usr/share/$pkgbase/ports/minimal\
        README.md\
        build/firmware*
    fi
  fi
  cd - > /dev/null
}

port-minimal-host() {
  cd $pkgbase-$pkgver/ports/minimal
  local cmd=$1
  if [[ $cmd = prepare ]]; then
    :
  else
    echo_header minimal
    if [[ $cmd = build ]]; then
      make BUILD=build-linux
    elif [[ $cmd = pack ]]; then
      install -D\
        build-linux/firmware.elf\
        $pkgdir/usr/bin/micropython-minimal
    fi
  fi
  cd - > /dev/null
}

port-nrf() {
  cd $pkgbase-$pkgver/ports/nrf
  local cmd=$1
  if [[ $cmd = prepare ]]; then
    [ -e drivers/bluetooth/s110_nrf51_8.0.0 ] ||\
      drivers/bluetooth/download_ble_stack.sh
  else
    local boards=$2
    local once
    for board in $boards; do
      echo_header nrf/$board
      if [[ $cmd = build ]]; then
        make BOARD=$board
      elif [[ $cmd = pack ]]; then
        install -Dm644 -t $pkgdir/usr/share/$pkgbase/ports/nrf/$board\
          build-$board/firmware*
        if [[ ! $once ]]; then once=1
          pkgdesc="Port of Micropython to boards: $boards"
          groups=('micropython-port' 'micropython-port-nrf')
          options=('!strip')
          arch=('any')
          install -Dm644 -t $pkgdir/usr/share/$pkgbase/ports/nrf README.md
        fi
      fi
    done
  fi
  cd - > /dev/null
}

port-pic16bit() {
  # needs microchip-mplabxc16-bin
  echo_header pic16bit
}

port-powerpc() {
  # needs gcc-powerpc
  cd $pkgbase-$pkgver/ports/powerpc
  local cmd=$1
  if [[ $cmd = prepare ]]; then
    :
  else
    echo_header powerpc
    if [[ $cmd = build ]]; then
      make
    elif [[ $cmd = pack ]]; then
      install -Dm644 -t $pkgdir/usr/share/$pkgbase/ports/powerpc\
        README.md\
        build/firmware*
    fi
  fi
}

port-qemu() {
  # needs riscv64-elf-gcc
  cd $pkgbase-$pkgver/ports/qemu
  local cmd=$1
  if [[ $cmd = prepare ]]; then
    :
  else
    local boards=$2
    local once
    for board in $boards; do
      echo_header qemu/$board
      if [[ $cmd = build ]]; then
        make BOARD=$board
      elif [[ $cmd = pack ]]; then
        install -Dm644 -t $pkgdir/usr/share/$pkgbase/ports/qemu/$board\
          build-$board/firmware*
        if [[ ! $once ]]; then once=1
          pkgdesc="Port of Micropython to boards: $boards"
          groups=('micropython-port' 'micropython-port-qemu')
          options=('!strip')
          arch=('any')
          install -Dm644 -t $pkgdir/usr/share/$pkgbase/ports/qemu README.md
        fi
      fi
    done
  fi
  cd - > /dev/null
}

port-renesas() {
  cd $pkgbase-$pkgver/ports/renesas-ra
  local cmd=$1
  if [[ $cmd = prepare ]]; then
    :
  else
    local boards=$2
    local once
    for board in $boards; do
      echo_header renesas-ra/$board
      if [[ $cmd = build ]]; then
        make BOARD=$board
      elif [[ $cmd = pack ]]; then
        install -Dm644 -t $pkgdir/usr/share/$pkgbase/ports/renesas-ra/$board\
          build-$board/firmware*
        if [[ ! $once ]]; then once=1
          pkgdesc="Port of Micropython to boards: $boards"
          groups=('micropython-port' 'micropython-port-renesas')
          options=('!strip')
          arch=('any')
          install -Dm644 -t $pkgdir/usr/share/$pkgbase/ports/renesas-ra README.md
        fi
      fi
    done
  fi
  cd - > /dev/null
}

port-rp2() {
  # needs CMake, picotool
  cd $pkgbase-$pkgver/ports/rp2
  local cmd=$1
  if [[ $cmd = prepare ]]; then
    :
  else
    local boards=$2
    local once
    for board in $boards; do
      echo_header rp2/$board
      if [[ $cmd = build ]]; then
        make BOARD=$board
      elif [[ $cmd = pack ]]; then
        install -Dm644 -t $pkgdir/usr/share/$pkgbase/ports/rp2/$board\
          build-$board/firmware*
        if [[ ! $once ]]; then once=1
          pkgdesc="Port of Micropython to boards: $boards"
          groups=('micropython-port' 'micropython-port-rp2')
          options=('!strip')
          arch=('any')
          install -Dm644 -t $pkgdir/usr/share/$pkgbase/ports/rp2 README.md
        fi
      fi
    done
  fi
  cd - > /dev/null
}

port-samd() {
  cd $pkgbase-$pkgver/ports/samd
  local cmd=$1
  if [[ $cmd = prepare ]]; then
    :
  else
    local boards=$2
    local once
    for board in $boards; do
      echo_header samd/$board
      if [[ $cmd = build ]]; then
        make BOARD=$board
      elif [[ $cmd = pack ]]; then
        install -Dm644 -t $pkgdir/usr/share/$pkgbase/ports/samd/$board\
          build-$board/firmware*
        if [[ ! $once ]]; then once=1
          pkgdesc="Port of Micropython to boards: $boards"
          groups=('micropython-port' 'micropython-port-samd')
          options=('!strip')
          arch=('any')
          install -Dm644 -t $pkgdir/usr/share/$pkgbase/ports/samd README.md
        fi
      fi
    done
  fi
  cd - > /dev/null
}

port-stm32() {
  cd $pkgbase-$pkgver/ports/stm32
  local shellopts=$(shopt -p nullglob)
  shopt -s nullglob
  local cmd=$1
  if [[ $cmd = prepare ]]; then
    :
  else
    local boards=$2
    local once
    for board in $boards; do
      mboots=('')
      if grep -q 'USE_MBOOT' boards/$board/mpconfigboard.mk\
      && ! grep -q 'USE_MBOOT = 0' boards/$board/mpconfigboard.mk\
      && [[ # mboot compilation fails on these boards
          $board != ADAFRUIT_F405_EXPRESS   &&
          $board != NUCLEO_H723ZG           &&
          $board != SPARKFUN_MICROMOD_STM32 &&
          $board != STM32H7B3I_DK           ]]
      then
        mboots+=(1)
      fi
      variants=('' boards/$board/mpconfigvariant_*.mk)
      for variant in "${variants[@]}"; do
        variant=${variant#boards/$board/mpconfigvariant_}
        variant=${variant%.mk}
        for mboot in "${mboots[@]}"; do
          build=${board}${variant:+-$variant}${mboot:+-mboot}
          echo_header stm32/${build}
          if [[ $cmd = build ]]; then
            if [[ ! $variant && $mboot ]]; then
              make -C mboot BOARD=$board
            fi
            make BUILD=build-$build BOARD=$board BOARD_VARIANT=$variant USE_MBOOT=${mboot:+0}
          elif [[ $cmd = pack ]]; then
            install -Dm644 -t $pkgdir/usr/share/$pkgbase/ports/stm32/$build\
              build-$build/firmware*
            if [[ ! $variant && $mboot ]]; then
              install -Dm644 -t $pkgdir/usr/share/$pkgbase/ports/stm32/$board-mboot\
                mboot/build-$board/firmware*
            fi
            if [[ ! $once ]]; then once=1
              pkgdesc="Port of Micropython to boards $boards"
              groups=('micropython-port' 'micropython-port-stm32')
              options=('!strip')
              arch=('any')
              install -Dm644 -t $pkgdir/usr/share/$pkgbase/ports/stm32 README.md
            fi
          fi
        done
      done
    done
  fi
  eval "$shellopts"
  cd - > /dev/null
}

port-unix() {
  echo_header unix
  cd $pkgbase-$pkgver/ports/unix
  if [[ $cmd = prepare ]]; then
    :
  elif [[ $cmd = build ]]; then
    make
  elif [[ $cmd = pack ]]; then
    make DESTDIR="$pkgdir" PREFIX=/usr install
  fi
  cd - > /dev/null
}

port-zephyr() {
  # needs zephyr-sdk - not tested
  echo_header zephyr
  cd $pkgbase-$pkgver/ports/zephyr
  if [[ $cmd = prepare ]]; then
    :
  elif [[ $cmd = build ]]; then
    west build -b frdm_k64f
  elif [[ $cmd = pack ]]; then
    :
  fi
  cd - > /dev/null
}
