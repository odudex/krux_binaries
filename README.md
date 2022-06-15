# Krux Binaries
Experimental compiled Krux binaries

# Flash Instructions:
Make ktool executable:
```
chmod +x ktool-linux 
```

To Flash Maix Amigo run:
```
./ktool-linux -B goE -b 1500000 maixpy_amigo_ips/kboot.kfpkg
```

To Flash M5stickV run:
```
./ktool-linux -B goE -b 1500000 maixpy_m5stickv/kboot.kfpkg
```

To Flash Maix Bit run:
```
./ktool-linux -B goE -b 1500000 maixpy_bit/kboot.kfpkg
```

To Flash Maix Dock run:
```
./ktool-linux -B dan -b 1500000 maixpy_dock/kboot.kfpkg
```

# Wiring

For Maix Bit connect Buttons between pins 22, 21 and GND
22 is for "Enter ", 21 is for "Page"

For Maix Dock connect a rotary encoder:

```
Encoder - Maix Dock
   GND <->  GND
     + <->  3V3
    SW <-> Pin 9
    DT <-> Pin 10
   CLK <-> Pin 11
```

# More Info
Code compiled on this binaries from: https://github.com/odudex/krux

Go to https://github.com/selfcustody/krux for official code and binaries

This binaries are NOT signed and for test purposes only
