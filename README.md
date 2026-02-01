# Population-based Optimization Algorithms Course

University of Trieste, "Applied Data Science and Artificial Intelligence" PhD program.

The course is 20 hours and it is 2.5 CFU.

## Exam Modalities

The final evaluation can be completed through one of the following three options.

Option 1 – Oral Presentation

A 10-minute presentation with slides of a scientific paper of your choice related to the topics of the course, namely, evolutionary computation and evolutionary algorithms. Conferences such as EvoStar, PPSN, and GECCO (this latter one has PDF freely available: https://dl.acm.org/conference/gecco/proceedings) can be used as references to identify suitable papers. Below a list of some papers that could be presented (mostly from GECCO, since they are typically shorter than journal papers and PDF are available for free):

https://doi.org/10.1016/j.swevo.2020.100646 

https://doi.org/10.1145/3512290.3528871 

https://doi.org/10.1109/CEC55065.2022.9870427 

https://doi.org/10.1007/978-1-4939-0375-7_11 

https://doi.org/10.1145/3712256.3726332 

https://doi.org/10.1145/3712256.3726364 

https://doi.org/10.1145/3712256.3726429

https://doi.org/10.1145/3712256.3726439 

https://doi.org/10.1145/3712256.3726469 

https://doi.org/10.1145/3712256.3726412 

https://doi.org/10.1145/3712256.3726448 

https://doi.org/10.1145/3712256.3726383 

https://doi.org/10.1145/3712256.3726343 

https://doi.org/10.1145/3712256.3726312 

https://doi.org/10.1145/3712256.3726484 

https://doi.org/10.1109/TEVC.2025.3611226 

https://doi.org/10.1109/TEVC.2025.3614086 

https://doi.org/10.1007/978-981-96-0077-9_12 

https://doi.org/10.1007/978-3-031-89991-1_7 

https://doi.org/10.1145/1830483.1830643 

https://doi.org/10.1007/s10710-013-9210-0 

 https://doi.org/10.1038/s41467-023-42664-x 

https://doi.org/10.1016/j.renene.2018.03.052 

Day and time of the presentation must be agreed with us via email and the presentation can be done remotely.

Option 2 – Project

The project consists of a small experimental study in which you design, implement, and analyze an evolutionary algorithm applied to a non-trivial optimization problem.

More specifically, the project should include the following components:


Problem selection
Choose a non-trivial single-objective optimization problem, i.e., a problem for which discovering the exact optimal solution, according to a single criterion, is not straightforward.
Examples include (but are not limited to):

combinatorial optimization problems (e.g., knapsack, scheduling, routing),

continuous function optimization,

hyper-parameter optimization,

symbolic regression,

simple control or design problems.

Algorithm implementation
Implement an evolutionary algorithm from scratch (including existing algorithms such as Genetic Algorithms, Evolution Strategies, Genetic Programming, Particle Swarm Optimization, Differential Evolution, etc.) to address the chosen problem. Each individual evolved by the algorithm represents a solution to the problem, and the fitness function must compute the quality of the given solution.

Experimental evaluation
Run the evolutionary algorithm for multiple independent repetitions (e.g., 10 repetitions; in the literature this number is often 30), using different random seeds.

Baseline comparison
Compare the evolutionary algorithm against a simple baseline (to be executed for multiple independent repetitions as well, the same number of repetitions employed for the evolutionary algorithm), such as:

random search, or

simulated annealing.

Results analysis
Discuss and compare the quality of the solutions obtained by the evolutionary algorithm and the baseline method, possibly supported by visualizations (e.g., box-plot, fitness trend) and a statistical test (e.g., Mann-Whitney U).

Ablation study
Perform an ablation study by analyzing how changes in one or more hyper-parameters affect performance.
Examples include:

mutation rate,

crossover rate,

population size and number of generations (e.g., 100 population size 10 generations vs. 10 population size 100 generations, so that the total number of fitness of evaluations is approximately the same, i.e., 1000),

selection pressure (e.g., tournament size in case of tournament selection).

Final report
Collect the code, plots, and written observations resulting from the analysis in an HTML/PDF report generated from a Jupyter notebook, which must be sent to us via email for evaluation.

A complete example of project targeting the OneMax problem with Genetic Algorithms will be provided.

Option 3 – Paper

You publish a paper related to something concerning evolutionary computation and you send to us via email the DOI of the published paper.

