
# Simulation-Based Process Optimization in Edible Oil Refining

## Overview
This project presents a simulation-based tool for optimizing edible oil refining using Python. It targets four major oils: mustard, soybean, sunflower, and groundnut. The model predicts critical refining parameters such as:
- NaOH dosage
- Final Free Fatty Acid (FFA)
- Refining loss
- Crude yield

The simulation incorporates BIS/FSSAI standards and real-world empirical constants to assist in lab prediction, industrial scaling, and automation integration.

## Features
- Dynamic simulation based on initial FFA input
- Error sensitivity analysis
- Graphical comparison of refining losses and yields
- Industry case study for real-world validation
- SCADA/Industry 4.0 integration-ready

## Technologies Used
- Python 3.x
- Matplotlib (for plotting)
- NumPy
- BIS/FSSAI and AOAC standards

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/oil-refining-simulation.git
   cd oil-refining-simulation
   ```

2. Install dependencies:
   ```bash
   pip install matplotlib numpy
   ```

3. Run the simulation:
   ```bash
   python simulate_refining.py
   ```

## Sample Input
```python
simulate_refining(oil_type='Mustard', input_ffa=2.8)
```

## Output
```
Final FFA: 0.07%
NaOH Required: 2.968%
Refining Loss: 1.29%
```

## Graphs
- Expression Yield vs Oil Type
- Refining Loss vs Oil Type

## Case Study
- 50 MT/day mustard oil refinery
- NaOH usage reduced by 6.2%
- Yield increased by 1.5%
- ROI achieved in under 3 months

## License
MIT License

## Author
Bhanu Pratap Singh  
Department of Oil Technology  
HBTU Kanpur, 2025-2026
