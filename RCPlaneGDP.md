# RC STOL Plane Group Design Project

---

<img src="images/RCPlaneDesign.jpg?raw=true"/>

### Task
In my undergraduate fourth year, I was involved in a group project where we were to design a remote control (RC) plane. We decided that we would aim to make an aircraft that is optimised to have the minimal take-off and landing distances possible. We would need to consider time and budgetary requirements, ensure we are within the bounds of regulatory boundaries, and then create a detailed conceptual design of the aircraft.

### Actions
-	I was first tasked with designing the wing. I began with the take-off distance formula, ensuring that all values were selected in such a way as to minimise the take-off distance.
-	I then reviewed the literature on vertical wing placement and dihedral value made selections for them.
-	Rudder, elevator, and control surface design was my next responsibility.
-	Finally, I was tasked with creating the general construction methodology.

### Results
-	The wingspan was set to the legal maximum, 2m. The NACA 22112 airfoil is selected due to it’s high CLmax. The aspect ratio of 10, sweep angle of 0 degrees, and taper ratio of one are selected due to historical precedence. The wing geometry is put into XFLR5 to gain some initial values of performance.

<img src="images/XFLRData.png?raw=true"/>

-	Vertical wing placement was selected due to the inherent roll stability and lack of internal fuselage structure, allowing for components within the fuselage to be uninhibited. Dihedral was deemed unnecessary for this design.
-	The control surfaces were designed in accordance with historical data.

<img src="images/ControlSurfaces.png?raw=true"/>

-	After considering multiple design choices, two spanwise spars provide the wing's structure, with the wings sliding into them which are screwed into place, with external struts used to minimise internal structures, since the drag they create at this speed is negligible.

### Technical Considerations
- **XFLR5**: Initial performance data of the wings (CL/CD graph, Lift slope (CL/alpha) graph, etc.)
