# SFP+ Port Cooling Solution for Ubiquiti Cloud Gateway Fiber

Custom 3D printed active cooling mod for Ubiquiti Cloud Gateway Fiber SFP+ ports. Improves airflow and helps reduce SFP+ module temperature.

## Parts Required

| Part | Qty | Link |
|------|-----|------|
| Sunon 5015 Blower Fan (12v) | 1 | [Digikey](https://www.digikey.com/en/products/detail/sunon-fans/MF50151V1-1B00U-A99/15996446) |
| USB to 5V Power Adapter | 1 | [Amazon](https://www.amazon.com/JacobsParts-Voltage-Trigger-Module-Type-C/dp/B0C7JXL2KH) |
| M3 Heatset Inserts | 2 | [Amazon](https://www.amazon.com/Threaded-Inserts-Soldering-Printed-Materials/dp/B0D7M3LJDL) |
| M3 x 8mm Screws | 2 | [Amazon](https://www.amazon.com/Socket-Screws-Bolts-Thread-100pcs/dp/B07CMQ1SQH) |
| 1mm VHB Double-Sided Tape | As needed | [Amazon](https://www.amazon.com/Gorilla-Heavy-Double-Sided-Mounting/dp/B082TQ3KB5) |

## Printed Parts

- **Main Housing**
- **USB Clamp**


## Assembly Instructions

1. **Insert** the M3 heatset inserts into the main housing using a soldering iron.
2. **Press** the 5015 blower fan into the housing. It should will be a snug fit or you might need to increase flow rate. 
3. **Solder** the 5015 fan wire leads to the positive/gound pads of the module, then clamp the module down with the clamp piece and 2 screws.
4. **Apply** VHB tape to the bottom two recesses under the housing/tab. You can then stick the assembled unit to your Cloud Gateway Fiber, aligning it with the SFP+ cage. 
5. **Connect** the fan to the USB power source and power on.

## Notes

- Make sure the USB power source is set to 5v for completely silent operation. You can also set it to 9v or 12v if you want more performance and are willing to accept a little more noise.
- ![image](https://github.com/user-attachments/assets/8f3a40e6-3058-4e50-bfdf-4470362212d7)

- Test fitment before final assembly. 

## License

MIT
