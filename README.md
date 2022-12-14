# from_theORy_to_application

This repository contains folly worked-out examples of several Operations Research (OR) problems, such as shortet path, vehicle routing, bin-packing problems. 
Each problem is briefly introduced and the basics of the underlying mathematical formulation are provided. Then, such formulation is translated into a 
Python code that sets up the problem and solves it using wither the commercial solver Gurobi (https://www.gurobi.com/. To use Gurobi, a license is needed, which is 
free (academic version) for students and all inetrested users affiliated to a university) or an open-source solver via implementation with PuLP (https://coin-or.github.io/pulp/). Whiel the first option is alway given due to the expertise and preferred coding routing of the authors, the second option is provided when possible to enhance the open-source dissemnation of the repository.

The target audience is people with limited knowledge of OR. Hence, we try to engage users with interesting examples and to relate them to practical problems
to show the potential (or at least the tip of the iceberg) of OR modeling. All OR problems are solved with Branch and Bound with default settings, 
unless differently speficied. This repository is about translating OR problems into OR models and, as such, does not contain algorithmic-oriented examples
such as column generation, matheuristic, branch-and-price, etc.

When possible, we will pair OR problems with a serious game equivament (e.g., a print-and-play board game) to enhance engagement and interaction among users. As this is a constantly-updated work in progress, we arehappy to receive any feedback concerning typos, errors, models or material that users would like to be uploaded. You an reach out to me (Alessandro Bombelli) at a.bombelli@tudelft.nl.

Other contributors are:
 - Bilge Atasoy (b.atasoy@tudeflt.nl)
 - Doris Boschma (d.boschma@tudelft.nl)
 - Stefano Fazi (s.fazi@tudelft.nl)
