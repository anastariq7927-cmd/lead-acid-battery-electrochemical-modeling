# lead-acid-battery-electrochemical-modeling
Experimental Electrochemistry · Physical Modeling · Thermodynamics · Energy Systems

## Overview

This project explores the electrical behavior of lead-acid batteries through an experimental study focused on discharge characteristics, electrical power, internal resistance, and temperature effects.

The work was carried out as part of an academic project on batteries in motorsport. It combines experimental measurements with physical interpretation to understand how operating conditions influence the electrical behavior of a battery.

The study provides a foundation for understanding how experimental data and simplified physical models can be used to analyze an electrochemical system.

## Objectives

The main objectives of this project are to:

- Analyze the electrical behavior of a lead-acid battery during discharge.
- Study the relationship between voltage, current, and electrical power.
- Estimate the battery's effective internal resistance using experimental measurements.
- Investigate the influence of temperature on discharge behavior.
- Connect experimental observations to simplified electrical and electrochemical models.
- Identify potential improvements for future experimental analysis and data-driven modeling.

## Experimental Methodology

The study relies on electrical measurements performed under controlled experimental conditions.

### 1. Discharge analysis

The battery's electrical behavior is investigated during discharge using a load resistor of:

$$
R_{\text{load}} = 70\ \Omega
$$

The voltage and current measurements are used to analyze the discharge response and the electrical power delivered to the load.

### 2. Temperature influence

The experiment examines battery behavior at three temperatures:

- $10\^\circ\mathrm{C}$
- $20\^\circ\mathrm{C}$
- $40\^\circ\mathrm{C}$

For the temperature comparison, the initial charging conditions are kept identical, with a charging duration of 8 minutes at a current of 150 mA.

This experimental setup provides a basis for comparing the electrical response under different thermal conditions.

### 3. Internal resistance estimation

At a reference temperature of $20\^\circ\mathrm{C}$, voltage measurements obtained at different discharge currents are used to estimate the effective internal resistance.

The study reports an estimated value of approximately:

$$
R_{\text{int}} \approx 5.1\ \Omega
$$

This value is an experimental estimate based on the simplified electrical model described below.

## Physical Modeling

### 1. Simplified electrical model

During discharge, the battery can be represented by an ideal electromotive force in series with an effective internal resistance.

The terminal voltage is approximated by:

$$
U = E - R_{\text{int}} I
$$

where:

- $U$ is the terminal voltage.
- $E$ is the ideal electromotive force.
- $R_{\text{int}}$ is the effective internal resistance.
- $I$ is the discharge current.

This model helps explain the voltage drop observed when current flows through the battery's internal resistance.

It is a simplified representation of the battery's behavior and does not capture every electrochemical process involved.

### 2. Electrical power

The electrical power delivered to the load is calculated using:

$$
P = UI
$$

where:

- $P$ is the electrical power.
- $U$ is the terminal voltage.
- $I$ is the electrical current.

This relationship makes it possible to examine how the voltage and current determine the power available during discharge.

### 3. Temperature and electrochemical kinetics

Temperature can influence the reaction kinetics and electrical behavior of an electrochemical system.

The Arrhenius relationship provides a theoretical framework for describing the temperature dependence of a reaction rate constant:

$$
k(T) = A \exp\left(-\frac{E_a}{R_g T}\right)
$$

where:

- $k(T)$ is the reaction rate constant.
- $A$ is the pre-exponential factor.
- $E_a$ is the activation energy.
- $R_g$ is the universal gas constant.
- $T$ is the absolute temperature in kelvin.

This relationship provides theoretical context for interpreting temperature-dependent electrochemical behavior. It is not presented as a parameterized predictive model fitted to the experimental measurements.

## Main Results and Observations

The experimental study supports several observations and analyses:

- **Discharge behavior:** Voltage and current measurements provide insight into the electrical response of the system under load.
- **Electrical power:** The relationship $P = UI$ connects the measured electrical quantities to the power delivered to the load.
- **Internal resistance:** The simplified model provides a method for estimating effective internal resistance, with a reported value of approximately $5.1\ \Omega$ at $20\^\circ\mathrm{C}$.
- **Temperature effects:** Measurements at $10\^\circ\mathrm{C}$, $20\^\circ\mathrm{C}$, and $40\^\circ\mathrm{C}$ provide a basis for comparing battery behavior under different thermal conditions.
- **Physical interpretation:** The equivalent-circuit model and Arrhenius relationship help connect electrical observations to the underlying physical and electrochemical principles.

The numerical results and experimental details are documented in the accompanying presentation.

## Limitations

This project is an experimental and physical modeling study. Its conclusions should be interpreted within the limits of the experimental setup.

- The equivalent-circuit model is a simplified representation of battery behavior.
- The estimated internal resistance depends on the experimental conditions and the assumptions used in the calculation.
- The temperature comparison is limited to the tested conditions and charging protocol.
- The Arrhenius relationship is included as a theoretical framework; no fitted kinetic parameters or validated temperature-prediction model are claimed.
- The project does not include a trained machine learning model or a complete predictive simulation of battery behavior.

These limitations identify opportunities for more systematic experimentation and quantitative modeling.

## Skills and Concepts

### Experimental analysis
- Interpretation of voltage and current measurements.
- Analysis of electrical discharge behavior.
- Comparison of measurements under different temperature conditions.
- Estimation of effective internal resistance.

### Physics and electrochemistry
- Lead-acid battery operating principles.
- Equivalent-circuit modeling.
- Electrical power calculations.
- Temperature dependence of electrochemical processes.
- Arrhenius relationship and reaction kinetics.

### Modeling approach
- Translation of physical assumptions into mathematical equations.
- Interpretation of experimental observations using simplified models.
- Identification of assumptions, limitations, and potential sources of uncertainty.

## Conclusion

This project applies experimental analysis and simplified physical modeling to the study of lead-acid battery behavior.

By examining discharge characteristics, electrical power, internal resistance, and temperature conditions, it demonstrates how electrical measurements can be interpreted using basic physical models.

The work also provides a starting point for further investigation into parameter estimation, predictive modeling, and the application of data-driven methods to electrochemical systems.

## Project Material

The repository contains the project presentation documenting the experimental setup, measurements, physical interpretation, and conclusions.

