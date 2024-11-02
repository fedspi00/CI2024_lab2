# CI2024_lab2

## Comparison of Greedy Algorithm and Evolutionary Algorithm for Solving the TSP problem

Two approaches used to solve TSP are the **Greedy Algorithm** and the **Evolutionary Algorithm**. Below, we compare these methods in terms of pros and cons and their execution time. We can see that the EA approach find considerably higher routes the larger the dataset, even though it's supposed to be effective for larger dataset.

## Differences Between Greedy Algorithm and Evolutionary Algorithm

### Greedy Algorithm

The Greedy Algorithm starts from an initial city and it iteratively selects the nearest unvisited city until all cities are visited, finally returning to the start city.

- **Pros**:
  - Easier to implement.
  - Efficient for small datasets.
- **Cons**:
  - Often yields suboptimal solutions.
  - Prone to getting stuck in local optima.

### Evolutionary Algorithm

The Evolutionary Algorithm maintains a population of possible TSP routes and evolves them over multiple generations to optimize the solution by appying selection, crossover, and mutation operators.

- **Pros**:
  - Can explore a broader solution space, avoiding local optima.
  - Effective for larger datasets.
- **Cons**:
  - Computationally intensive.

## Comparison Table

| Feature     | Greedy Algorithm | Evolutionary Algorithm |
| ----------- | ---------------- | ---------------------- |
| **China**   | 63962.92km       | 692846.33km            |
| **US**      | 48050.03km       | 162248.26km            |
| **Russia**  | 42334.16km       | 53177.77km             |
| **Italy**   | 4436.03km        | 4442.54km              |
| **Vanuatu** | 1475.53km        | 1345.54km              |
