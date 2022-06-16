# MCDM-in-Laptop-Purchasing

## Ranking algorithms —  Multi-Criteria Decision solving techniques

Algorithms to solve complex decision-making problems influenced by multiple criteria. We will discuss why we need such techniques and explore available algorithms in the cool skcriteria python package
Suppose you have a decision to make — like buying a house, or a car, or even a guitar. You don’t want to choose randomly or get biased by someone’s suggestion, but want to make an educated decision. For this, you gathered some information about the entity you want to buy (let’s say it’s a Laptop). So you have a list of N Laptops with their price information. As usual, we won’t want to spend more, we can just sort the Laptops by their price (in ascending order) and pick the top one (with the smallest price), and we are done! This was decision making with a single criterion. But alas if life is so easy :) We would also like the laptop to have good processor or core, big screen, Less weight, and some more. Here, you want to choose a Laptop with the smallest price, but the Less weight  and so on. This problem can’t be so easily solved by simple sorting. Enter multi-criteria decision-making algorithms!

## Generic methodology
Most of the basic multi-criteria decision solvers have a common methodology which tries to,
- Consider one attribute at a time and try to maximize or minimize it (as per the requirement) to generate optimized score.
- Introduce weights to each attributes to get optimized weighted scores.
- Combine the weighted scores (of each attribute) to create a final score for an entity (here Laptop).



