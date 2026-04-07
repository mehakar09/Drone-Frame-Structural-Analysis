# Drone Frame Structural Analysis

This project presents the structural analysis of a quadcopter drone frame using Autodesk Fusion 360.

## Objective
To evaluate the structural strength and deformation of the drone frame under static loading conditions.

## Software Used
- Autodesk Fusion 360 (Simulation Workspace)

## Analysis Performed
- Static Stress Analysis

## Model Description
The drone frame consists of:
- Central body plates
- Four extended arms
- Motor mounting ends

A simplified simulation-ready model was created from the original CAD design for structural evaluation.

## Assumptions
- Equal downward load applied on all four arms
- Static loading condition
- Simulation performed on simplified structural geometry

## Results

### Safety Factor
- Minimum Safety Factor: 15.00
- Design Status: Very Strong / Safe

### Displacement
- Maximum Displacement: ~0.012 mm

### Conclusion
- The drone frame is structurally safe under the applied static loading conditions.
- The design shows very low displacement and high structural strength.
- The frame can potentially be optimized further for weight reduction.

## Files Included
- `drone_design.f3z` → Original CAD model
- `drone_simulation_model.f3z` → Simulation-ready Fusion 360 model
- `drone_analysis_report.pdf` → Simulation report
- `images/` → Screenshots of setup and results

## Future Scope
- Modal analysis for vibration behavior
- Weight optimization of frame
- Comparative study using different materials