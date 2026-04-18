# Turbofan Engine Design, and Optimisation for an Airbus A320neo

---

<img src="images/AirbusEngine.jpg?raw=true"/>

### Task

In my postgraduate studies at the University of Glasgow, I was tasked with designing a three shaft turbofan jet engine for the Airbus A320neo. I carried out a constraint analysis, a cycle analysis, and component design for the turbine and compressor stages using the free vortex assumption, all while optimising parameters to improve the specific fuel consumption (sfc) and thrust force of the engine.

### Actions
- Using Microsoft Excel, a constraint analysis was created to calculate the design point, allowing me to ascertain the thrust which will be required of the engine, and the expected sfc.
<img src="images/ConstraintAnalysis.png?raw=true"/>

- The cycle analysis was conducted using MATLAB where stagnation pressures and temperatures before and after each stage of the engine were calculated.

- Design parameters were altered in order to optimise the design; these parameters were the bypass ratio, turbine entry temperature (TET), fan pressure ratio, and the pressure ratios for the high and intermediate pressure compressors. Values which were being optimised included sfc, specific thrust, efficiencies, engine diameter, etc.

- MATLAB was also utilised during the component design section where I calculated and optimised the spans of individual compressor and turbine blades along with their angles relative to flow direction at the spanwise locations of the root, middle and tip of the blades using the free vortex assumption.

- Another parametric study was conducted at this stage, varying values of stage loading, flow coefficient, and reaction to ensure that the angles of the blades were within a reasonable range.

### Results

- Calculation of design point (0.45), thrust (174kN per engine at take-off), and expected sfc (0.012kg/kNs), all fall within ranges expected for modern engines.

- Parametric study for the cycle analysis returned results that would be suitable for the Airbus A320neo and other similarly sized modern aircraft, for example: the overall pressure ratio = 19.8, bypass raio = 8, TET = 1500k, engine diameter = 2.53m.
<img src="images/APBypassDiameter?raw=true"/>

- Compressor and turbine blade geometries and angles successfully meet the necessary pressure ratio values calculated in the cycle analysis before, whilst also being reasonable given the restrictions of modern material selection and blade cooling systems. Some resulting design values: number of IP compressor stages = 7, and HP compressor stages = 6, IP shaft speed = 7800rpm, HP shaft speed = 9000rpm.
  
- The value for sfc was anticipated in the constraint analysis to be 0.012kg/kNs, but was calculated at 0.0198kg/kNs in the cycle analysis. For a modern turbofan engine this is an unacceptable level for fuel efficiency. To keep weight as low as possible, I was restricted by my project specification to have each of the three turbines be kept to a single stage, meaning the three pressure ratios were kept low. I would recommend increasing the number of turbine stages and increasing bypass ratio, allowing for higher pressure ratios and therefore, a lower sfc at the detriment to weight reduction.

### Technical Considerations

- **Microsoft Excel**: Constraint analysis

- **MATLAB**: Cycle analysis and component design
