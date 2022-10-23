# REF1451-N64-Gameshark-Pro

This was the final revision of the N64 Gameshark produced by Datel. They were clearly trying to cut as many costs as they could with this one. The parallel port was left on so that you couldn't tell the difference between this Gameshark and the older versions simply be examining the exterior of the cartridge. The parallel port is completely isolated and non-functioning, however. It is unknown at this time if the QuickLogic FPGA contains logic for the components that weren't included in this revision. It is curious that the A17 and A18 lines were connected on the EEPROMs between each other. It may be that they were simply remnants from modifying the original schematic prior to generating this PCB by the Datel engineer responsible for this project, but it may also be that they did run to the FPGA at one point as well. The A17 and A18 lines are only necessary if you are using an SST 28LF040 instead of the very common SST 29LE010. The rom supports both and early versions of the Gameshark have been found in the wild with the SST 28LF040's. This board was only meant to support the SST 29LE010's due to the disconnected A17 and A18 lines.

Be careful soldering the QuickLogic FPGA. It is sensitive to heat.

PCB Thickness: 1.2 mm

![image](https://github.com/Modman/REF1451-N64-Gameshark-Pro/blob/main/REF1451%20Optimized.png)
