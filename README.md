# Comparison of time complexity in factorizing large bi prime numbers using Grover’s and Shor’s algorithm

This is the quantum circuit implementation of the research paper on "Comparison of time complexity in factorizing large bi prime numbers using Grover’s and Shor’s algorithm". Link to the paper can be found [here](https://www.researchgate.net/publication/343484871_Comparison_of_time_complexity_in_factorizing_large_bi_prime_numbers_using_Grover%27s_and_Shor%27s_algorithm)

## Content of the code

- A function for the Grover's circuit is created to carry out the circuit formation.
- Using the **'qasm simulator'** we find the most appropriate values using the circuit and represent the results in the form of a histogram and a Density Matrix plot.
- We have our ideals plots.
- The same is then repeated with IBMQ backend simulations of **IBMQ Yorktown** and **IBMQ Melbourne** with 5 qubits and 15 qubits operative capacities respectively. 

