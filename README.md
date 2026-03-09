# VSCODE
launch.json for debugging esp32s3 in visual studio code with cortex-debug extension.

For Windows users: you will likely need to install a custom USB driver. Download and run https://zadig.akeo.ie (you might need to run it as an administrator). Click Options > List all devices. Select the USB JTAG/serial debug unit (Interface 2) from the device drop-down menu. Click the drop-down arrow on the button and select Install Driver. Click the Install Driver (or Reinstall Driver) button.

you also have to install openocd from https://github.com/xpack-dev-tools/openocd-xpack/releases and unpack it and put into program files, also add it to Path in enviromental variabels.


