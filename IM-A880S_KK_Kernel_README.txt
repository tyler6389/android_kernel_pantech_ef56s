How to Build
    1. Get Toolchain (arm-eabi-4.7) and install
       (Visit android git server or codesourcery)

    2. modify below lines in build_kernel.sh and run
          1) modify below lines
                $ export ARCH=arm
                $ export PATH=$(pwd)/../toolchain/arm-eabi-4.7/bin:$PATH
                $ export CROSS_COMPILE=arm-eabi-
          2) run build_kernel.sh
                $ ./build_kernel.sh

    3. Output Files
      -	kernel : kernel/arch/arm/boot/zImaze
      -	module : kernel/drivers/*/*.ko

    4. WLAN URL
      - https://www.codeaurora.org/cgit/quic/la/platform/vendor/qcom-opensource/wlan/prima/tag/?h=LNX.LA.2.7.3&id=LNX.LA.3.5.1-09210-8x74.0

Vega LTE-A F2FS&EXFAT backport Count
