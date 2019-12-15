# MDMC-CARP-Benchmark-Tool
Tool for generating MDMC-CARP randomly benchmark instances

Users can enter number of nodes, number of edges, number of tasks, total capacity of the
vehicle Q, a minimum number of depots minDepot, a maximum number of depots maxDepots, a minimum
cost minCost and a maximum cost maxCost, a minimum demand minDem and a maximum demand
maxDem. These all parameters are stored in a XML file, named setting found in the same directory as
the tool executable. The executable code and the setting file can be found in[]. The number of depots
is generated randomly between minDepot and maxDepot and they are located randomly on N d distinct
nodes. The distance cost between nodes is generated randomly between minCost and maxCost. The
demand assigned to each task varies according to m. First, a random integer dem between minDem and
maxDem is generated. Second, if m = 1, then the demand of the single product is 4×dem. If m = 2, then
demands of product 1 and product 2 are respectively dem and 3×dem. Finally, if m = 3, then the demands
of product 1, product 2 and product 3 are respectively dem, dem and 2 × dem.
