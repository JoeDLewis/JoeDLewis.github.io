# Response of a T-Beam Under Load, Using Three Methods

---

<img src="images/TBeam.png?raw=true"/>

### Task

In my fourth year of my undergraduate degree, I was tasked with determining the physical response of a T-beam under load through use of experimentation, mathematical theory, and finite element analysis (FEA), in order to discuss the differences in the methods.

### Actions

- I Conducted an experiment where a T-beam has loads of 150N and 300N applied to it with strain gauges measuring the strain experienced by the beam at various points around the beam.

- Recreated the Beam geometry in ANSYS DesignModeller and ensured high mesh quality.

- Conducted a FEA simulation with the same conditions as the experiment in ANSYS Structural using the 3D Solid body method.

- The Bernouli-Euler theory of elasticity and Macauley’s method allowed for the same conditions of the experiment to be recreated using only mathematical theory.

### Results

- The theory and FEA methods differed in deflection distance by only one percent.

- The theory method differed from the experiment by 3% for the 150N load and 6% for the 300N load.

- The FEA deflection results differed from the experiment by only 2% and 5% respectively making it the most effective method for simulating the experiment.

### Technical

- **DesignModeller**: CAD Software

- **ANSYS Static Structural**:3D Solid Body Finite Element Analysis (FEA)
