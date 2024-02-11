# Tesla Coil Project

## Overview

This project aims to design and simulate the operation of a Tesla coil using `atopile`. It focuses on the design of the primary coil, secondary coil, capacitor, and spark gap, as well as setting the coupling coefficient between these components.

## Design Details

### Components

- **Primary Coil**: A coil with an inductance of 10mH.
- **Secondary Coil**: A coil with an inductance of 100mH.
- **Capacitor**: A capacitor with a specific capacitance.
- **Spark Gap**: A device to generate electrical sparks.

### Coupling Coefficient

We use the `VirtualCoupling` module to conceptually represent the coupling coefficient between the primary and secondary coils. The coupling coefficient is set to 0.1.

## Experimental Results

The experiment confirmed the operation of the Tesla coil and evaluated the efficiency of energy transfer between the primary and secondary coils. The results showed expected behavior, but optimization of the coupling coefficient is necessary.

## Issues and Improvement Suggestions

- **Optimization of the Coupling Coefficient**: The current coupling coefficient is conceptual and needs to be optimized through physical design and experimentation.
- **Enhancing Safety Measures**: Handling high voltages requires enhanced safety measures.

## References and Resources

- [atopile Official Documentation](https://pypi.org/project/atopile/)
- [Basics of Tesla Coils](https://example.com/tesla_coil_basics)

## Community Sharing

This project is open-source and available on GitHub. Feedback and improvement suggestions are highly welcome. Please join the discussion on [Discord](https://discord.gg/example) as well.
