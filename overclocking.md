# Raspberry Pi overclocking.
Keep in mind that you can't **hurt** the Pi with overclocking. The worst that can happen is that it will not boot.
You can just tone down the OC config to an acceptable level.

⚠️ IMPORTANT: If you will be overclocking to values higher than 1.5GHz, a heatsink with thermal pad or compound is strongly recommended.
Or you can just hang a small 3V fan on the CPU. That works as well. 

⚠️ IMPORTANT (2): Make sure you have a powerful power brick. Minimum: 5V, 2A

## Lets get started!
To overclock the Raspberry Pi 3 and 4 you have to find the config.txt file on the SD card.
Turn of your Pi, take out the SD card / USB drive and plug it in ya PC! 

Locate the config.txt file and open it with your favourite text editor.

### If you are on a Raspberry Pi 4:
Paste this on the top of the text file:
```
over_voltage=7 #Forces the Pi to allow more voltage in
arm_freq=2200 #Overclocks the Pi to 2.2GHz (Value is in MHz)
arm_turbo=1 #Allows the Pi to "Turbo" when needed.
gpu_freq=850 #Overclocks the GPU to 0.85GHz 
gpu_mem=256 #Sets the GPU memory to 256 (Recommended)
```

WIP. I'll finish this soon
