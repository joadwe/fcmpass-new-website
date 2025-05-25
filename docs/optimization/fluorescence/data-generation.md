# Data generation

## Requirements

### Sample preparation

1. Vortex rainbow peak beads bottle on a medium setting for 5 seconds.&#x20;
2. Pipette 500 µL of DPBS in two FACS tubes. Label one tube ’DPBS” and the second tube ’Beads’.&#x20;
3. Add 3 drops of QbSure beads to the ’Beads’ tube and vortex for 5 seconds

### Cytometer setup

4. Ensure cytometer is clean and that -Height and -Area statistics are set to be collected on all parameters and that all parameters are on.&#x20;
5. On the Cytek Aurora, set window extension to 0. On the CytoFLEX platform turn on ’High Acquisition Mode’.&#x20;
6. Create a pseudocolor plot with FSC-H on the X-Axis and (488 nm) B-SSC-H on the Y-Axis and make sure both parameters are being plotted on a linear-scale.&#x20;
7. Create a histogram plot with (405 nm) V-SSC-H on the X-Axis and make sure it is plotted on a log-scale.&#x20;
8. Set the cytometer triggering threshold to (405 nm) VSSC-H. All samples should be acquired with the lowest flow rate, typically 10-15 µL min-1.&#x20;
9. Acquire the DPBS tube while viewing the histogram plot from Step 7&#x20;
10. Adjust the detector gain or trigger threshold until the instrument noise is being acquired at 1000 events/sec. The instrument noise floor is distinct from detected background events in sheath as it has a sharp increase. In a system with debris there may be a tail that elongates out of this this sharp peak.&#x20;
11. Acquire the ’Beads’ tube from Step 3. Using the plot from Step 6 adjust the FSC and B-SSC gain until the single bead population is clearly visible and can be easily gated from the doublet population to the top right of it. Use the Violet SSC trigger settings identified in Step 10 .&#x20;
12. Creating a gate around the single bead population named ’Bead Gate’.&#x20;
13. Adjust the stopping criteria of the instrument to record until 10,000 events are acquired on ’Bead Gate’ drawn in Step 1.

Detector setting incrementation (DSI)

14. DSI can now be performed by recording the ’Beads’ tube at multiple fluorescent detector gains, leaving the trigger threshold and light scatter gains consistent. It is recommended that a recording of at least 10 fluorescent detector settings is taken. Including more increments within a DSI set will result in being more confident of the subsequent optimal detector settings.&#x20;
15. Fluorescent channels can be cross calibrated to determine lower limit of detection for the channel in calibrated units in the FCMPASS software. A cross calibration between the desired MESF bead and QbSure beads should be acquired at a fluorescent detector gain where all MESF bead populations are on-scale and fully resolved from the noise.

