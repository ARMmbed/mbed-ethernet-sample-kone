mbedConnectorInteface endpoint example for KONE (Ethernet)

You will need to replace the contents of security.h with yours. 

You can import this project into the online IDE at https://developer.mbed.org

 - Right-click on "My Project"

 - Select import "from URL" 

 - Enter the following URL: https://github.com/ARMmbed/mbed-ethernet-sample-kone

 - DO NOT SELECT "Update all libraries"... ensure that remains UNCHECKED 
 
To compile locally, you need to install "mbed-cli"

Example (Linux):

 % pip install -U "mbed-cli"

Once installed:

 % git clone https://github.com/ARMmbed/mbed-ethernet-sample-kone

 % cd mbed-ethernet-sample-kone

 % mbed deploy

 % mbed target K64F

 % mbed toolchain GCC_ARM

 % mbed compile -m K64F -t GCC_ARM -c -j0

The compiled binary will be found in here:

 % cd .build/K64F/GCC_ARM/mbed-ethernet-sample-kone.bin

Lastly, copy the "bin" file to your mbed device and reset the device
