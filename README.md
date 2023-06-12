# Instances for the Two-Echelon Multi-Trip Vehicle Routing Problem with Pickups and Time Windows (2E-MT-VRP-PTW)
This github repository contains the test instances used by Lehmann and Winkenbach in their 2023 Submission "A Matheuristic for the Multi-Trip Two-Echelon Vehicle Routing Problem with Pickups and Time Windows" to the Special Issue "Innovative models and methods for managing transport logistics" in Transportation Research Part C: Emerging Technologies.

The instances are a modification of the instances created by Dellaert, Saridarq, Van Woensel, Crainic (2018) 
Branch-and-Price–Based Algorithms for the Two-Echelon Vehicle Routing Problem with Time Windows. Transportation Science 
53(2):463-479  by adding an indicator to each customer on whether their demand represents a pickup or a delivery.

The folder [2E MT VRP PTW Instances Lehmann Winkenbach](2E MT VRP PTW Instances Lehmann Winkenbach) contains all 240 test instances in `.csv`.

Each table has the following columns:
- latitude: Latitude of the node
- longitude: Longitude of the node
- start TW: The start time window of the node (only applies to customer nodes)
- end TW: The end time window of the node (only applies to customer nodes)
- demand: The demand of the node (only applies to customer nodes)
- service time: The time it takes to service the node (only applies to satellite and customer nodes)
- type: The category of the node, i.e. depot, satellite or customer
- index: The row index of the node 
- ID: The specific ID of each node
- customer type: The indicator on whether the node is a pickup or delivery node (only applies to customer nodes)
