MT6572_KONKA_V850
===========================================

export PATH=${PATH}:~/Your_Toolchain_PATH/

cd kernel directory

export TARGET_PRODUCT=Your device name
export MTK_ROOT_CUSOMT=../mediatek/custom/ 
export MTK_PATH_PLATFORM=../mediatek/platform/mt6572/kernel/ 

cd kernel
export PATH=${PATH}:~/Your_toolchain_directory/bin/arm-linux-android-eabi-     (DOWNLOAD NDK)
export ARCH=arm
make menuconfig     (add some kernel futures)
make zImage
WAIT,..........
ARCH/arm/boot/ready
