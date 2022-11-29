# Path planning problem

In this example, we will learn how to model path planning as an OR problem. In our example, we have robots moving along a rectangular grid. Their goal
is to move from their origin node to their destination node while minimizing the overall (across all robots) distance transversed. Hence, it is a
collaborative problem in nature. The main routing-related constraints are

- at most one robot can occupy the same node at the same time
- each edge of the grid can be used by maximum one robot at the same time (considering both directions)

If we want to make the problem more challenging, we can add this constraint as well

- no robot can ever use the origin/destination node of any other robot while moving across the grid