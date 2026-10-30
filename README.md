
# Three-Phase Power System Analysis Using MATLAB and PowerWorld Simulator

## Overview

This project focuses on three-phase electrical power system analysis using MATLAB and PowerWorld Simulator. It covers load-flow studies and short-circuit fault analysis to evaluate the operating characteristics of interconnected power systems under normal and abnormal conditions.

Various numerical methods are implemented for load-flow analysis, while symmetrical and unsymmetrical faults are studied at different bus locations and transmission line sections.

## Objectives

- Perform three-phase power system load-flow analysis.
- Determine bus voltage magnitudes and phase angles.
- Calculate active and reactive power flows in transmission networks.
- Analyse symmetrical and unsymmetrical fault conditions.
- Evaluate fault currents at different bus and transmission line locations.
- Study network performance under normal and fault conditions.
- Compare MATLAB analysis results with PowerWorld Simulator results.

## 1. Load Flow Analysis

Load-flow analysis is performed to determine the steady-state operating conditions of the three-phase power system.

### Numerical Methods

**1. Gauss–Seidel Method**
- Iterative method for solving load-flow equations.
- Determines bus voltages through successive voltage updates.
- Evaluates convergence characteristics.

**2. Newton–Raphson Method**
- Uses iterative calculations based on the Jacobian matrix.
- Determines bus voltage magnitudes and phase angles.
- Provides efficient convergence for power system analysis.

**3. Fast-Decoupled Load Flow Method**
- Uses the approximate decoupling of active power and voltage angle, and reactive power and voltage magnitude.
- Reduces computational complexity.
- Evaluates network operating conditions and convergence.

### Parameters Analysed

- Bus voltage magnitudes.
- Voltage phase angles.
- Active and reactive power.
- Transmission line power flows.
- Real and reactive power losses.
- Load-flow convergence characteristics.

## 2. Three-Phase Fault Analysis

Fault analysis is performed to investigate the behaviour of the power system under short-circuit conditions.

### A. Symmetrical Faults

- Three-Phase (LLL) Fault.
- Three-Phase-to-Ground (LLLG) Fault, where considered.

### B. Unsymmetrical Faults

- Single Line-to-Ground (LG) Fault.
- Line-to-Line (LL) Fault.
- Double Line-to-Ground (LLG) Fault.

### Fault Locations

Fault analysis is carried out at different locations in the power network:

- Different bus locations.
- Transmission line sections.
- Selected points between interconnected buses.

### Parameters Analysed

- Fault current magnitudes.
- Bus voltages during fault conditions.
- Positive sequence components.
- Negative sequence components.
- Zero sequence components.
- Short-circuit levels.
- Fault characteristics at different network locations.

## 3. Software and Tools

- MATLAB – Numerical computation and power system analysis.
- PowerWorld Simulator – Power system network modelling and simulation.

## 4. Result Analysis and Validation

The project involves analysing and comparing power system characteristics under different operating conditions.

The analysis includes:

- Comparison of load-flow results obtained using different numerical methods.
- Evaluation of bus voltage profiles.
- Analysis of active and reactive power distribution.
- Examination of convergence behaviour.
- Comparison of symmetrical and unsymmetrical fault currents.
- Evaluation of fault conditions at different network locations.
- Validation of simulation results using PowerWorld Simulator.

## 5. Applications

- Electrical power system planning and operation.
- Transmission network analysis.
- Short-circuit and fault studies.
- Power system protection studies.
- Voltage profile assessment.
- Network performance evaluation.

## Conclusion

This project demonstrates the application of numerical techniques and simulation tools for three-phase power system analysis. Load-flow and fault studies provide insights into the steady-state operating conditions and short-circuit behaviour of interconnected electrical networks.

MATLAB implementations and PowerWorld simulations are used to analyse network performance and understand power system behaviour under normal and abnormal operating conditions.

---

**Domain:** Electrical and Electronics Engineering – Power Systems

**Tools:** MATLAB, PowerWorld Simulator

**Topics:** Load Flow Analysis, Gauss–Seidel Method, Newton–Raphson Method, Fast-Decoupled Load Flow, Symmetrical Fault Analysis, Unsymmetrical Fault Analysis.
