# Leakage Reduction in CMOS with Stacked Transistors
 Experimental proof of concept for stacked transistor method to reduce leakage current in sub-micro (45nm) technologies 

## Abstract
In CMOS circuits, the reduction of the threshold voltage due to voltage scaling leads to increase in sub threshold leakage current and hence, static power dissipation. Technique called LECTOR for designing CMOS gates is proposed which significantly cuts down the leakage current without increasing the dynamic power dissipation.<br/>
The proposed technique introduces two leakage control transistors (a p-type and a n-type) within the logic gate for which the gate terminal of each leakage control transistor (LCT) is controlled by the source of the other. In this arrangement, one of the LCT's is always "near its cut-off (NCO) voltage" for any input combination. This increases the resistance of the path from V<sub>dd</sub> to ground leading to significant decrease in leakage currents.The significant feature of LECTOR is that it works effectively in both active and idle states of the circuit, resulting in better leakage reduction compared to other techniques. Further, the proposed technique overcomes the limitations posed by other existing methods for leakage reduction.

## Technique Motivation
With rapid progress in semiconductor technology, chip density has increased. This scaling of transistor feature sizes has provided a remarkable advancement with the increase in speed and frequency of operation and hence higher performance is achieved but the power dissipation also increases. High power dissipation reduces the battery service life.</br>
Furthermore, Power and performance are always traded off to meet the system requirements. Power has a direct impact on the system cost.
If an IC is consuming more power, then a better cooling mechanism would be required to keep the circuit in normal conditions. Otherwise, its performance is degraded and on continuous use it may be permanently damaged.Therefore, power dissipation has become critical concern in today's VLSI system design.</br>

