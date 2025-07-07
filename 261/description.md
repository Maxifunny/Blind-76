# LeetCode 261: Graph Valid Tree

## Description

Given `n` nodes labeled from `0` to `n - 1` and a list of undirected edges, determine if the given graph is a **valid tree**.

A graph is considered a valid tree if it meets all of the following conditions:

- It is **connected** — there is a path between any two nodes.
- It contains **no cycles**.
- It has exactly **n - 1 edges**.

## Input

- An integer `n` representing the number of nodes.
- A list `edges`, where each element is a pair `[a, b]` representing an undirected edge between nodes `a` and `b`.

## Output

- Return `True` if the input graph is a valid tree.
- Return `False` otherwise.

## Constraints

- `1 <= n <= 2000`
- `edges.length <= 2000`
- Each edge is a pair `[a, b]` with `0 <= a, b < n`

## Example 1

```python
n = 5
edges = [[0,1], [0,2], [0,3], [1,4]]
Output: True
