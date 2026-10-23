# EECE 7205 In-Class Work: Binary Search Trees

Worked solutions for the binary search tree in-class assignment (Problems 1 to 3).

Northeastern University, Electrical and Computer Engineering, Fall 2026.

## Contents

`INCLASSWORK04_KARISHMAPREMNATH.pdf` covers all three problems on the array
`arr = {50, 30, 70, 20, 40, 60, 80, 35, 45, 65, 75}` (n = 11).

- **Problem 1, Insert.** Cases 3 to 6: larger key, deep insert turning both ways,
  duplicate key, and sorted input. Includes the full insertion table for all 11 keys
  and one combined INSERT procedure.
- **Problem 2, Search.** Cases 3 to 6: a path that turns, a key that is absent,
  a key larger than every key in the tree, and finding the minimum and maximum.
- **Problem 3, Delete.** Cases 3 to 6: one right child, one left child, two children
  whose successor is the right child, and deleting the root. Includes one combined
  DELETE procedure.

Each case gives the rule and explanation, the pseudocode, and the tree before and after.
Height is counted in edges, so a single node has height 0 and the tree built in
Problem 1 has height 3.
