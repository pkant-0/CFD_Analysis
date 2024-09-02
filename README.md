# CFD_Analysis
CFD analysis of the drag torque due to viscous drag of the fluid on the submerged motor rotor, we'll break the task into two main parts:

    Analytical Calculation: This will provide an initial estimate of the drag torque using the given dimensions and speeds.
    CFD Analysis (ANSYS Based): This will give a more accurate simulation of the drag forces using ANSYS.

1. Analytical Calculation

We can start by estimating the drag torque analytically using the following steps:
Drag Torque Calculation

The drag torque due to viscous drag in a fluid can be estimated using the following formula:

Tdrag=12×CD×ρ×A×v2×RTdrag​=21​×CD​×ρ×A×v2×R

Where:

    CDCD​ = Drag coefficient (depends on the shape of the rotor and flow regime)
    ρρ = Density of the fluid (for water, it is approximately 1000 kg/m³)
    AA = Projected area of the rotor
    vv = Relative velocity of the rotor surface to the fluid (in m/s)
    RR = Radius of the rotor (in m)

Steps to Calculate:

    Determine the relative velocity:
        v=ω×rv=ω×r where ωω is the angular velocity in rad/s (calculated from RPM), and rr is the radius.
    Calculate the projected area:
        AA depends on the dimensions of the rotor, which will be extracted from the provided Excel file.
    Estimate the drag coefficient:
        CDCD​ can be estimated based on empirical data or standard references depending on the shape of the rotor.
    Compute the drag torque:
        Using the formula above for different air gaps.
