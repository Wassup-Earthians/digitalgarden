---
{"dg-publish":true,"permalink":"/project-logs/week-6/"}
---

# 19/02/2026 (Thursday)

One team member focused on implementing and designing the inverter circuit in Proteus simulation software, ensuring that the MOSFET switching stage and associated components were correctly arranged for proper operation. Simultaneously, another member carried out the necessary theoretical calculations for the low-pass filter, determining appropriate values of the inductor and capacitor required to smooth the square wave output and approximate a sinusoidal waveform. The third member studied the working principle of a function generator, particularly how it generates a square wave signal through electronic switching and waveform shaping circuits, as this signal is used to drive the MOSFETs in the inverter circuit.

# 13/02/2026 (Friday)

On 20-02-2026 (Friday), the team proceeded to design and implement the low-pass filter in the simulation to smooth the inverter’s square wave output and observe whether the resulting waveform approximated a sine wave. The output was analyzed using the virtual oscilloscope; however, during testing we encountered an issue with MOSFET switching. It was observed that the current supplied directly from the Arduino was insufficient to properly drive the MOSFET gates, which affected the switching performance of the inverter circuit. To address this problem, the team decided that an external gate driver IC would be required to provide adequate gate drive current.

# Work Assigned

| Team member    | Work Assigned                                                         |
| -------------- | --------------------------------------------------------------------- |
| Aditya Jagdale | Search for the gate driver IC                                         |
| Balraj Singh   | Prepare approximate BOM                                               |
| Amar Bardale   | Search for the components required in local shops and online websites |
| Aditya Bhagwat | Search for the components required in local shops and online websites |

# Problems Faced

1. To drive the mosfet from arduino current.
2. Need to redesign the low pass filter.