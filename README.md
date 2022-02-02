# Assignment2-nagulapally
# Madhuri Nagulapally
###### My favorite place to buy food is Walmart
###### walmart is an **American** __multinational__ retail corporation.As of October 31, 2021, Walmart has **10,566** stores. The stores focus on  Walmart's major sales categories: groceries,pharmacy and at some stores, fuel. Walmart is located 0.7 miles away from my house.
___
## Directions
* Get on I-70 W from E 12th St 
* Follow I-29 N to US-71 N in Jefferson Township. Take exit 56A from I-29 N
* Follow US-71 N to your destination in Maryville
___

# The list of food I would recommend
1. Milk
2. Eggs
3. Bread
4. Fruits

[*Link to AboutMe*](https://github.com/Madhuri221998/assignment2-nagulapally/blob/main/AboutMe.md)

___

## Sports and Activities Recomended

These are the few sports I would recomend to try with the location to be played and the cost for equipments

| Name of the Sport/Activity | Location | Approx Price for equipment |
| --- | --- | --- |
| Basketball | Rectangular Court | $100 |
| Cricket | Large Grass Field | $50 |
| Golf | Court | $250 |
| Soccer | Large Fields | $150 |

___

# Quotes

`Live as if you were to die tomorrow. Learn as if you were to live forever...`

 *- Mahatma Gandhi*

`A person who never made a mistake never tried anything new...`

*– Albert Einstein*

___

# Code

`The idea behind DFS is to go as deep into the graph as possible, and backtrack once you are at a vertex without any unvisited adjacent vertices.`

`It is very easy to describe / implement the algorithm recursively: We start the search at one vertex. After visiting a vertex, we further perform a DFS for each adjacent vertex that we haven't visited before. This way we visit all vertices that are reachable from the starting vertex.`


```
vector<vector<int>> adj; // graph represented as an adjacency list
int n; // number of vertices
vector<bool> visited;
void dfs(int v) {
    visited[v] = true;
    for (int u : adj[v]) {
        if (!visited[u])
            dfs(u);
    }
}
```

[*link of the source code*](https://cp-algorithms.com/graph/depth-first-search.html)