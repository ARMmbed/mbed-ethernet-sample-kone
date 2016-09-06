mbedConnectorInteface endpoint example with Device Management (Ethernet)

Adaptations:

 - FXOS8700CQ integrated accelerometer used instead of MMA7660

 - Added LCDResource for the mbed Application Shield LCD

To compile locally, you need to install "mbed-cli"

Example (Linux):

 % pip install -U "mbed-cli"

Once installed:

 % git clone https://github.com/ARMmbed/mbed-ethernet-sample-ibm

 % cd mbed-ethernet-sample-ibm

 % mbed deploy

 % mbed target K64F

 % mbed toolchain GCC_ARM

 % mbed compile -m K64F -t GCC_ARM -c -j0

The compiled binary will be found in here:

 % cd .build/K64F/GCC_ARM/mbed-ethernet-sample-ibm.bin

Lastly, copy the "bin" file to your mbed device and reset the device
