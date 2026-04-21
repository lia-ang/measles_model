# Scenario-Based Modeling of 2025 Texas Measles Outbreaks

This repository contains the code and data supporting the study:  
**_“Assessing MMR Vaccination Strategies in Texas: A Scenario-Based Modeling Study of Measles Outbreaks”_**  
Bi et al., 2025 
DOI: [https://doi.org/10.1101/2025.03.25.25324613]

---

## Summary

This study evaluates the impact of the MMR vaccination strategies on measles transmission in Texas during the 2025 outbreak. Using a stochastic age-structured SEIR-HD model, we compare outbreak outcomes under different vaccine uptakes scenarios (baseline, 5% decrease, 5% increase).

---

## Repository Structure

- `README.md`: Project summary, instructions, and citation information.

code
- `Measles_Model_Finalized.ipynb`: Parameter estimation and scenario simulation code for S. Carolina.
- `Measles_Model_Finalized_5-19Vaccination.ipynb`: Scenario simulation code for 5-19yr vaccinations.
- `Measles_Model_Finalized_ChildhoodVaccination.ipynb`: Scenario simulation code for 0-4yr vaccinations.
- `Measles_Model_Finalized_5-19Vaccination.ipynb`: Scenario simulation code for state-specific vaccination data in all age groups (Florida and S. Carolina).
- `map1_1.ipynb`: Simulation code for all counties under the baseline scenario.
- `map2_1.ipynb`: Simulation code for all counties under 5% reduced vaccination scenario.
- `map3_1.ipynb`: Simulation code for all counties under 5% improved vaccination scenario.

data
- `S.Carolina_case.csv`: Reported measles cases in S.Carolina.
- `United_States_subnational_Texas_M_overall_contact_matrix_85.csv`: Age-specific contact matrix for Texas.

---

## Conference

### MIDAS 2025 
Speed talk and poster at the MIDAS 2025 annual symposium. [more](https://github.com/bikaiming93/measles_model/tree/main/materials)
