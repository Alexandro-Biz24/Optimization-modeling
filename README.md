# Linear Programming & Simplex Algorithm
This project implements the simplex method to solve linear optimization problems using Python and SciPy.

**Project description**
Linear optimization is an essential technique for maximizing or minimizing an objective function under linear constraints.

This project implements the simplex algorithm, an efficient method for solving linear optimization problems applied to concrete cases such as :

**Princpial step :**

1.  Rewriting the problem in standard form :
    From an initial system combining our objective function and the associated constraints
       <img src="initial_systeme.png" alt="initial systeme" width="200">

    
    - Any equality constraint can be written as two inequalities
      <img src="standardform1.png" alt="equialities to inequalities" width="200">
      
    - Any ≥ constraint can be written as a ≤ constraint:
      <img src="standardform2.png" alt="superior to inferior to inequalities" width="200">
      
      
    - Any minimization problem can be turned into a maximization
      problem:
      <img src="standardform3.png" alt="minimization to maximization" width="200">
     
  
