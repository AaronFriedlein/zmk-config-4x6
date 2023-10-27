# Custom 4x6 with Nav switch Dactyl Manuform Keyboard: zmk-config

Hey 👋 welcome. Use this repo to generate your own ZMK keymap. It assumes you are using nice!nano v2 with your taiko dactyl manuform.
This is a fork of the original repo which intends to implement a 4x6 physical configuration with a 5x6 logical configuration
in order to utilize a 5 way nav switch in the thumb cluster.

## Get started
1. Fork this repo.
2. `git clone https://github.com/yourusername/zmk-config.git` 
3. Open up `config/dactyl_manuform_5x6.keymap` and edit the keymap (aka keyboard layout) to your liking.
4. `git push`
5. Check the Github Actions section. Your new firmware file should be available for download.
6. Unzip the firmware.zip file. You should see two files: `dactyl_manuform_5x6_left-nice_nano_v2-zmk.uf2` and `dactyl_manuform_5x6_right-nice_nano_v2-zmk.uf2`.
7. Flash the nice!nanos with your new firmware. For details on flashing your new firmware, see: https://docs.taikohub.com/customizing-keyboard-layout-with-zmk. You can skip `Step 1. Download the configuration file for the left and right piece of your keyboard`. Use your own .uf2 instead of the ones provided on the website.

## Parts
1. Pro-Micro x2
2. Battery x2 https://typeractive.xyz/products/lithium-battery-110mah
3. Dual QI Transmitter https://www.alibaba.com/product-detail/Dual-charge-fast-charging-wireless-charger_60799913536.html
4. QI Reciever x2
5. Voltage stepper
6. Nav Switch https://www.aliexpress.us/item/2255800623296209.html?gatewayAdapt=glo2usa4itemAdapt
