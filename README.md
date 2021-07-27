This is a network analysis project with messy real-world data.  To prevent any "github dorking" I will refrain from using sensitive keywords in this description.

### Data
***
We have JSON data pertaining to investment proposals and actual investment projects as well as incorporation documents for many many businesses.  We are trying to find out who are the most important players among the group.


### Method
***
We will use the typical method of creating a node graph (bidirectional) with a few types of nodes and project a bipartite graph connecting nodes of similar types through nodes of distinct types to create a representation of a social network.  We will then weight the edges of the graph and subtract the edges with the lower weights progressively until we are left with some useful information.
