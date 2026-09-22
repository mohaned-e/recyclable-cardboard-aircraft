# Recyclable Cardboard Aircraft: Iterative Structural Design & Flight Validation

A catapult-launched cardboard glider, developed through three structural design iterations to minimise mass while maintaining structural integrity, with performance validated against real flight test data.

Team project — University of Manchester, Aerospace Design coursework (2025).

**My contribution**: led the project team and distributed tasks across the group; led the physical aircraft design and laser-cutting manufacture of all three iterations; produced the project summary video.

---

## Project overview

The aircraft was developed through three design iterations:
1. **Iteration 1** — structurally robust but overweight.
2. **Iteration 2** — introduced lightening holes to reduce mass.
3. **Iteration 3 (final)** — optimised material distribution while maintaining structural integrity, with lightening holes deliberately concentrated toward the rear of the airframe to shift the centre of gravity forward, reducing the amount of nose ballast otherwise required.

**Result: an approximate 26% mass reduction** between the solid (non-perforated) baseline and the final perforated design, confirmed via FEA to maintain structural integrity.

---

## Launch & trajectory modelling

- Catapult launch parameters (elastic force vs. extension) were characterised experimentally, showing a **near-linear relationship between extension and elastic energy**.
- Aerodynamic coefficients: drag coefficient of **0.05**, approximated from Clark Y aerofoil reference data at a **12° angle of attack**; lift coefficient refined by matching the simulated trajectory against Week 10 flight test data.
- A loss coefficient was derived by comparing the theoretical launch velocity against the actual launch velocity measured via video analysis of the test flights.
- **Target**: 18 m landing distance for an aircraft mass of 0.561 kg, requiring a theoretical launch velocity of 5.62 m/s.
- Catapult position 7 was selected as the closest achievable match (predicted 5.86 m/s); the actual measured launch velocity was **5.74 m/s**.
- **Simulated landing distance: 18.97 m against an 18 m target — accurate to within 3%.**

---

## Structural validation (FEA)

- A static FEA study applied a **5.5 N upward load** (representing aerodynamic lift) to the final design.
- Results: **0.39 mm maximum wing deflection**, **0.44 mm fuselage deflection**, with a safety factor greater than 1.
- The solid vs. perforated (lightening-hole) models were directly compared to quantify the mass-saving effect of the hole pattern while confirming the airframe walls retained structural integrity.

---

## Flight testing & validation

Flight time, landing distance, and trajectory shape were measured via video analysis across Week 10 test flights, and the spreadsheet model's parameters were iteratively tuned until the simulation matched the empirical results. The final design met the 18 m target, validating the mass-reduction strategy end-to-end — from spreadsheet model, through FEA, to physical flight test.

**Observed deviation**: the aircraft's actual flight path curved right of the predicted straight trajectory, attributed to a wind gust from open building doors during testing rather than a structural or modelling fault.

---

## Known assumptions & limitations

- The drag coefficient was held constant across the flight envelope rather than modelled as a function of angle of attack.
- Elastic-to-kinetic energy conversion in the catapult was assumed ideal, with a separate empirical loss coefficient applied afterward; this linear relationship was only validated over a 0.6–1 m catapult extension range due to a lack of data outside it.
- The static FEA modelled aerodynamic lift only, and did not include the point load acting on the empennage during launch — a likely contributor to observed fuselage bending after repeated test flights.
- Cardboard was modelled as a homogeneous, isotropic material for CAD/FEA purposes, a simplification of its real layered, directional structure.
- Test conditions were limited by video capture frame rate (affecting trajectory analysis precision), non-ideal manufacturing tolerances, and structural fatigue accumulating across repeated test flights — the fuselage was observed to bend progressively after several flights, increasing skin drag over time.

---

## Video

**[▶ Project summary & flight test footage](https://youtu.be/mbl3f1Ac6y4?si=Gd0bXzZZfy35qnm3)**

---

## Author

Mohaned Elkurdi — Aerospace Engineering, University of Manchester
Team lead, physical design & manufacture, project video
[Other team members credited: Yat Cheung, Xinyi Feng, Eva Kielstra Ortega, Adesh Krishna, Yithro Teo]
