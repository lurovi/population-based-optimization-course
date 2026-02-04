# Population-based Optimization Methods Course

University of Trieste, "Applied Data Science and Artificial Intelligence" PhD program.

The course is 20 hours and it is 2.5 CFU.

The course “Population-based Optimization Methods” focuses on a collection of methods, generally inspired by natural phenomena, used for optimization and where multiple solutions to the same problems are iteratively improved. In this course we will explore genetic algorithms, genetic programming, evolution strategies, particle swarm optimization, differential evolution, how to represent particular problem domains (e.g., graphs and permutations), neuroevolution, common parallelization techniques, and a brief introduction to the runtime analysis of bio-inspired algorithms.

## Exam Modalities

The final evaluation can be completed through one of the following four options.

### Option 1 – Oral Presentation

A 10/15 minutes presentation with slides of a scientific paper of your choice related to the topics of the course, namely, evolutionary computation and evolutionary algorithms. Conferences such as EvoStar, PPSN, and GECCO (this latter one has PDF freely available: https://dl.acm.org/conference/gecco/proceedings) can be used as references to identify suitable papers. Below a list of some papers that could be presented (mostly from GECCO, since they are typically shorter than journal papers and PDF are available for free):

- https://doi.org/10.1016/j.swevo.2020.100646 

- https://doi.org/10.1145/3512290.3528871 

- https://doi.org/10.1109/CEC55065.2022.9870427 

- https://doi.org/10.1007/978-1-4939-0375-7_11 

- https://doi.org/10.1145/3712256.3726332 

- https://doi.org/10.1145/3712256.3726364 

- https://doi.org/10.1145/3712256.3726429

- https://doi.org/10.1145/3712256.3726439 

- https://doi.org/10.1145/3712256.3726469 

- https://doi.org/10.1145/3712256.3726412 

- https://doi.org/10.1145/3712256.3726448 

- https://doi.org/10.1145/3712256.3726383 

- https://doi.org/10.1145/3712256.3726343 

- https://doi.org/10.1145/3712256.3726312 

- https://doi.org/10.1145/3712256.3726484 

- https://doi.org/10.1109/TEVC.2025.3611226 

- https://doi.org/10.1109/TEVC.2025.3614086 

- https://doi.org/10.1007/978-981-96-0077-9_12 

- https://doi.org/10.1007/978-3-031-89991-1_7 

- https://doi.org/10.1145/1830483.1830643 

- https://doi.org/10.1007/s10710-013-9210-0 

- https://doi.org/10.1038/s41467-023-42664-x 

- https://doi.org/10.1016/j.renene.2018.03.052 

Day and time of the presentation must be agreed with us via email and the presentation can be done remotely.

### Option 2 – Project

The project consists of a small experimental study in which you design, implement, and analyze an evolutionary algorithm applied to a non-trivial optimization problem.

More specifically, the project should include the following components:

**Problem selection**

Choose a non-trivial single-objective optimization problem, i.e., a problem for which discovering the exact optimal solution, according to a single criterion, is not straightforward.
Examples include (but are not limited to):

- combinatorial optimization problems (e.g., knapsack, scheduling, routing),

- continuous function optimization,

- deceptive problems,

- hyper-parameter optimization,

- symbolic regression,

- simple control or design problems.

**Algorithm implementation**

Implement an evolutionary algorithm from scratch (including existing algorithms such as Genetic Algorithms, Evolution Strategies, Genetic Programming, Particle Swarm Optimization, Differential Evolution, etc.) to address the chosen problem. Each individual evolved by the algorithm represents a solution to the problem, and the fitness function must compute the quality of the given solution.

**Experimental evaluation**

Run the evolutionary algorithm for multiple independent repetitions (e.g., 10 repetitions; in the literature this number is often 30), using different random seeds.

**Baseline comparison**

Compare the evolutionary algorithm against a simple baseline (to be executed for multiple independent repetitions as well, the same number of repetitions employed for the evolutionary algorithm), such as, random search or simulated annealing. The computational budget employed should always be the same (e.g., if you run an evolutionary algorithm for 10 generations with a population size of 100, then you are likely going to compute 1000 fitness evaluations, this should be compared with a random search/simulated annealing consisting of 1000 iterations to ensure fairness and soundness).

**Results analysis**

Discuss and compare the quality of the solutions obtained by the evolutionary algorithm and the baseline method, possibly supported by visualizations (e.g., box-plot, fitness trend) and a statistical test (e.g., Mann-Whitney U, Holm-Bonferroni correction).

**Ablation study**

Perform an ablation study by analyzing how changes in one or more hyper-parameters affect performance.
Examples include:

- mutation rate,

- crossover rate,

- population size and number of generations (e.g., 100 population size 10 generations vs. 10 population size 100 generations, so that the total number of fitness of evaluations is approximately the same, i.e., 1000),

- selection pressure (e.g., tournament size in case of tournament selection).

**Final report**

Collect the code, plots, and written observations resulting from the analysis in an HTML/PDF report generated from a Jupyter notebook, which must be sent to us via email for evaluation.

Examples of projects running Python 3.12 (requirements are provided as well) are available as notebooks with the corresponding HTML files in the 'example_projects' folder.

The aforementioned structure is a standard pipeline for an evolutionary algorithms-related project. However, if you have another type of practical project in mind that you would like to explore (e.g., multi-objective optimization, analytical analysis), feel free to propose your idea to us and we will let you know whether it is suitable as a project.

### Option 3 - Report/Survey

You write a short report/survey (max 5 pages excluding references) in which you describe a specific topic concerning evolutionary computation and you perform a literature review on the papers related to that topic in a structured way. Examples of topics are: Boolean functions optimization with evolutionary algorithms, evolutionary computation for interpretable machine learning or reinforcement learning, evolutionary algorithms to address control or design problems, mathematical analysis of evolutionary algorithms, evolutionary algorithms applied to artificial life. The report must be sent to us via email for evaluation. You can use whatever template you want. An example of Overleaf LaTeX template is available at [https://overleaf.com/latex/templates/springer-nature-latex-template/myxmhdsbzkyd](https://overleaf.com/latex/templates/springer-nature-latex-template/myxmhdsbzkyd).

### Option 4 – Paper

You publish a paper related to something concerning evolutionary computation or in which you apply evolutionary algorithms to solve a given task and you send to us via email the DOI of the published paper for evaluation.

