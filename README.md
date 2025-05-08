# Current macOS

Current Version: macOS Sonoma 14.5

# Hardware

* CPU: AMD Ryzen 7 7700
* Board: ASRock B650M Riptide
* RAM: 32 GB (2x16GB) Adata DDR5 6000Mhz CL32
* GPU: XFX RX 580
* Wifi/BT: None

# BIOS

* iGPU shoudl be disabled
* Default settings is ok, no change required for macOS

# Note

* The original VBIOS of XFX RX580 seems not being supported (can't boot with OC), So I using the Asus.RX580.8192.171010.rom instead. According to the memory frequenzy and brand of your RAM, you could choose another VBIOS.
* I just used a part of USB port in motherboard, as I'm planning to place the machine in the cabinet. It is better to do custom of your USB mapping again which could solve many power/sleep/restart issues.
* Only using a DP cable seems to wake the system from sleep properly, while using HDMI results in a black screen (though the system still wakes up normally)
* RX580 should use legacy model to boot, there in Boot->CSM->Enabled, lanuch Video OpROM Policy -> legacy only
