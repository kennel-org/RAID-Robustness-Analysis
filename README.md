# RAID Robustness Analysis Based on AFR

This project contains functions and simulations to calculate and compare the failure rates of different RAID configurations (RAID1, RAID5, RAID6) and single disk setups over a period of 5 years. It uses both theoretical calculations and Monte Carlo simulations to determine these failure rates and plots the results for visualization. The program also finds intersection points between single disk and RAID failure rates.

## Features

- **Theoretical Calculations**: Compute failure rates for RAID and single disk setups.
- **Monte Carlo Simulations**: Simulate failure rates using random sampling.
- **Visualization**: Plot the results for easy comparison and analysis.
- **Intersection Points**: Identify where single disk and RAID failure rates intersect.

## Requirements

- Python 3.x
- NumPy
- Matplotlib
- SciPy

## Usage

1. Install the required packages:
   ```bash
   pip install numpy matplotlib scipy
   ```

2. Run the Jupyter Notebook to execute the simulations and view the plots.

## License

This project is licensed under the MIT License.
