## Summary Locations

Summary locations are at the end of each notebook and in this file

## Summaries

### Notebook 1

I learned a Bell state can be created with a Hadamrd gate followed by a CNOT gate. Furthermore I learned/relized that measuring an entangled state with different observables will result in a value of 0

### Notebook 2

I learned how to construct a bell state and then manipulate it to form different bell states. Furthermore, I used primitive input output objects to obtain the results. In the VQE section I learned how to use the EstimatorV2 with the PUB to gain the expected value results for the energy state. It was interesting to see the function used for optimizing the cost function, however I am curious to learn more how the cost function is being called.

### Notebook 3

In this notebook I learned about the 6 different transpilation stages that exist in Qiskit. These include initialization, layout, routing, translation, optimization, and scheduling. Furthermore, I learned more about the generate_pass function and how to pass different parameters to it to cause specific optimizations to happen.

Initialization - Convert 3+ qubit gates to 2 and 1 qubit gates

Layout - Assign the qubit numbers to the optimal qubits on the hardware

Routing - Perform qubit swaps

Translation - Translate to native HW gates

Optimization - Run optimization steps repeatedly to reduce the depth

Scheduling - Include any specific hardware features like delays