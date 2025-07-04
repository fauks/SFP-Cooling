# SFP+ Port Cooling Solution for Ubiquiti Cloud Gateway Fiber

Custom 3D printed active cooling mod for Ubiquiti Cloud Gateway Fiber SFP+ ports. Improves airflow and helps reduce SFP+ module temperature.

![IMG_20250531_111327](https://github.com/fauks/SFP-Cooling/blob/main/UCG-Fiber-USB-5015/images/IMG1.jpg)



## Parts Required

| Part | Qty | Link |
|------|-----|------|
| *Sunon 5015 Blower Fan (12v, 5200rpm) OR | 1 | [Digikey](https://www.digikey.com/en/products/detail/sunon-fans/MF50151V1-1B00U-A99/15996446) |
| *Sunon 5015 Blower Fan (12v, 4200rpm) | 1 | [Digikey](https://www.digikey.com/en/products/detail/sunon-fans/MF50151V2-1B00U-A99/15996444) |
| USB to 5/9/12v Trigger Module | 1 | [Amazon](https://www.amazon.com/JacobsParts-Voltage-Trigger-Module-Type-C/dp/B0C7JXL2KH) |
| M3 Heatset Inserts | 2 | [Amazon](https://www.amazon.com/Threaded-Inserts-Soldering-Printed-Materials/dp/B0D7M3LJDL) |
| M3 x 8mm Screws | 2 | [Amazon](https://www.amazon.com/Socket-Screws-Bolts-Thread-100pcs/dp/B07CMQ1SQH) |
| 1mm VHB Double-Sided Tape | As needed | [Amazon](https://www.amazon.com/Gorilla-Heavy-Double-Sided-Mounting/dp/B082TQ3KB5) |

*5200RPM @ 5v is recommended for any enclosed spaces or warm environments > 24c ambient, 4200RPM @ 5v for open spaces or cool environments < 24c. 5200RPM @ 5v is slightly more quiet than a Noctua NF-A4x20 at full speed. 4200RPM @ 5v is nearly inaudible. 
4200RPM @ 9v may be needed for some applications especially if you are not sensitive to noise. 5200RPM @ 9v will not perform better than 4200RPM @ 9v so its pointless to go that high. 
## Printed Parts

- **Main Housing**
- **USB Clamp**
  
Supports are only needed for the VHB tab on the main housing and wiring cutout on the USB clamp piece.

![image](https://github.com/fauks/SFP-Cooling/blob/main/UCG-Fiber-USB-5015/images/IMG6.png)



## Assembly Instructions

1. **Insert** the M3 heatset inserts into the main housing using a soldering iron.
2. **Press** the 5015 blower fan into the housing. It should will be a snug fit or you might need to increase flow rate. 
3. **Solder** the 5015 fan wire leads to the positive/gound pads of the module, then clamp the module down with the clamp piece and 2 screws.
4. **Apply** VHB tape to the bottom two recesses under the housing/tab. You can then stick the assembled unit to your Cloud Gateway Fiber, aligning it with the SFP+ cage. 
5. **Connect** the fan to the USB power source and power on.

![IMG20250531193708](https://github.com/fauks/SFP-Cooling/blob/main/UCG-Fiber-USB-5015/images/IMG2.jpg)

![IMG20250531193801](https://github.com/fauks/SFP-Cooling/blob/main/UCG-Fiber-USB-5015/images/IMG3.jpg)



## Notes

- Make sure the USB power source is set to 5v for completely silent operation. You can also set it to 9v or 12v if you want more performance and are willing to accept a little more noise. These jumper pads limit the maximum negotiation from the power brick, so if you have a 5v brick and have it set to 9v, it will still only output 5v. If your brick is PD capable and can output 12v, if you have the module set to 5v it will only output 5v regardless. 
- ![image](https://github.com/fauks/SFP-Cooling/blob/main/UCG-Fiber-USB-5015/images/IMG5.png)

- Test fitment before final assembly. You may need to fine tune your flow rate to get the right amount of friction for the fan to keep it in place. 

## License

GPLv3
