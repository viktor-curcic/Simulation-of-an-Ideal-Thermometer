
# Maxwell’s Demon Thermometer Simulation  
*Statistical physics simulation of energy exchange between an ideal gas and Maxwell’s Demon.*

## Project Description  
This simulation models an ideal gas system interacting with Maxwell’s Demon to investigate:  
- The demon’s behavior as a non-perturbative thermometer  
- Validation of Maxwell-Boltzmann velocity distributions  
- Energy exchange dynamics between microscopic systems  

Key result: The demon’s energy distribution follows `P(E_d) ~ exp(-E_d/k_BT)` while maintaining gas temperature within 0.15% of initial value (299.55 K vs 300 K).

## Repository Contents  
- `simulacija.ipynb`: Jupyter notebook containing the complete simulation and analysis  
- `Idealni_termometar.pdf`: Full project report (in Serbian) with theoretical background and results  

## Getting Started  
1. Run the simulation:  
   ```
   jupyter notebook simulacija.ipynb  
   ```  
2. View the pre-executed notebook cells for immediate results  

## Key Parameters  
- 400 helium particles (4 g/mol) at 300 K  
- Demon modifies velocity components with \(\delta \in [-5v_0, 5v_0]\)  
- 50,000-150,000 iterations per simulation  

[Download Full Report](Idealni_termometar.pdf)  
