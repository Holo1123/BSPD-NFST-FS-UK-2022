# BSPD-NFST-FS-UK-2022
BSPD PCB design for our FS ICE car for FS UK 2022 , NUST STUDENT FORMULA TEAM.
The BPS and TPS signals are compared to voltage levels set using the Pots and the delays required are achieved using RC circuits.

This design was made according the 2022 Formula Student UK rulebook.

<H2>T11.6 Brake System Plausibility Device<H2>

T11.6.1 A standalone non-programmable circuit, the BSPD, must open the shutdown circuit, see 
EV6.1 and CV4.1, when hard braking occurs, whilst
• [CV ONLY] the throttle position is more than 25 % over idle position.
The shutdown circuit must remain open until power cycling the LVMS or the BSPD may reset 
itself if the opening condition is no longer present for more than 10s

T11.6.2 The action of opening the shutdown circuit must occur if the implausibility is persistent for 
more than 500 ms.

T11.6.3 The BSPD must be directly supplied, see T1.3.1, from the LVMS, see T11.3.

T11.6.4 Standalone is defined as there is no additional functionality implemented on all required 
Printed Circuit Boards (PCBs). The interfaces must be reduced to the minimum necessary 
signals,i.e. power supply, required sensors and the shutdown circuit. Supply and sensor-signals must not be routed through any other devices before entering the BSPD.

T11.6.5 To detect hard braking, a brake system pressure sensor must be used. The threshold must 
be chosen such that there are no locked wheels and the brake pressure is 30bar.

T11.6.7 It must be possible to separately disconnect each sensor signal wire for technical 
inspection.

T11.6.8 All necessary signals are System Critical Signal (SCS), see T11.9.




![alt text](https://github.com/Holo1123/BSPD-NFST-FS-UK-2022/blob/main/easyeda_7TEWsL2oap.png?raw=true)
