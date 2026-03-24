---
{"dg-publish":true,"permalink":"/project-logs/week-7/","updated":"2026-03-23T17:26:54.226+05:30"}
---

# 26/02/2026 (Thursday)

The team compiled a detailed list of the electronic components required for the project after checking their availability in both local electronic component shops and online platforms. During the same session, the issue related to MOSFET gate driving observed earlier in the simulation was addressed. The team studied several MOSFET gate driver IC datasheets and analyzed their specifications such as gate drive voltage, current capability, and compatibility with the switching configuration used in our circuit. Based on this analysis, a suitable gate driver IC was selected and implemented in the simulation, which resolved the MOSFET driving problem

# 27/02/2026 (Friday)

 After successfully resolving the MOSFET gate driving issue in the simulation by selecting an appropriate gate driver IC, the team proceeded to redesign the low-pass filter (LPF) stage of the inverter circuit. Since the switching characteristics of the circuit changed after incorporating the gate driver, it was necessary to re-evaluate the filtering stage to obtain a smoother output waveform. The team therefore recalculated the required values of the inductor and capacitor for the LPF based on the switching frequency and desired cutoff frequency, ensuring that the filter could effectively attenuate higher-order harmonics present in the square wave output.

# Work Assigned

| Team member    | Work Assigned                            |
| -------------- | ---------------------------------------- |
| Aditya Jagdale | Went to purchase components              |
| Balraj Singh   | Debug the small issues in the simulation |
| Amar Bardale   | Documentation of progress                |
| Aditya Bhagwat | Went to purchase components              |

# Problems Faced

1. Unavailability of components of desired configurations, leading to redundant search for worse case scenario, when no shop has those components.
2. Debugging and redesigning the circuit neatly and cleanly.