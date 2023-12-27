## CPBPC for BP-MCF

This repo contains problem instances and results of the paper "Computing Bi-Path Multi-Commodity Flows with Constraint Programming-based Branch-and-Price-and-Cut" published on the INFORMS Journal on Computing.

The code is not available due to the confidentiality of Huawei France.

### Problem instance source

10 topologies and 180 instances from [SNDlib](http://sndlib.zib.de)

10 topologies and 180 instances from [Internet Topology Zoo](http://www.topology-zoo.org) 

9 topologies and 162 instances randomly generated

### Problem instance format

NumberOfNodes NumberOfEdges NumberOfDemands

[For each edge:]

Origin Destination Capacity PrimaryCost SecondaryCost Delay

...

[For each demand:]

Origin Destination Bandwidth DelayDifferenceThreshold

...