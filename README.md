
# Heat Equation Solution in One Dimension

## Project Overview

This project provides a detailed exploration of the heat equation in one dimension, a fundamental equation in physics that governs the diffusion of heat within a material over time. The notebook includes theoretical background, mathematical formulations, and numerical solutions using Python. The project was completed as part of an assignment for MMP II.

## Table of Contents

- [Project Overview](#project-overview)
- [Installation](#installation)
- [Usage](#usage)
- [Theory](#theory)
- [Visualization](#visualization)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## Installation

To run this project, you'll need to have Python installed along with the following libraries:

- `numpy`
- `matplotlib`
- `ipywidgets`
- `simpy`
- `mpl_toolkits`

You can install the required packages using pip:

```bash
pip install numpy matplotlib ipywidgets simpy
```

Alternatively, you can install the packages listed in `requirements.txt` if included in the repository.

## Usage

1. Clone this repository:

```bash
git clone https://github.com/yourusername/heat-equation-solution.git
cd heat-equation-solution
```

2. Open the Jupyter Notebook:

```bash
jupyter notebook "Heat Equation Sol (1).ipynb"
```

3. Run the cells in the notebook to explore the solutions to the heat equation.

## Theory

The heat equation is a partial differential equation (PDE) that describes the distribution of heat (or variation in temperature) in a given region over time. It is expressed as:

```math
\frac{\partial u}{\partial t} = \alpha \frac{\partial^2 u}{\partial x^2}
```

Where:
- `u(x, t)` is the temperature distribution.
- `t` is time.
- `x` is the spatial coordinate.
- `\alpha` is the thermal diffusivity of the material.

## Visualization

The project includes visualizations that help understand the solution to the heat equation in one dimension. The visualizations are created using `matplotlib` and can be interactively explored using `ipywidgets`.

## Contributing

Contributions to this project are welcome. Please feel free to submit a pull request or open an issue.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

This project was completed as part of an assignment for the course MMP II. Special thanks to the course instructor and the Department of DPAM for their guidance and support.
