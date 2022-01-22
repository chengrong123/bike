## Structure of instance files (or how to read them).

small - Five-node network;
ND - Nguyen–Dupuis network;
SF - Sioux Falls network; 

Files "auto_small.csv", "auto_ND.csv", and "auto_SF.csv" present cars traveling information on the three networks.
	For each line, it contains the following information:
    		<link>: ID of the link
    		<origin>: origin of the link
    		<destination>: destination of the link
    		<free-flow travel time>: free-flow travel time for a vehicle traveling through the link 
   		<capacity>: capacity of the link
   		<Theta>: value of theta - parameter used in the lower-level model
   		<Psi>: value of Psi - parameter used in the lower-level model
 
 
Files "bike_small.csv", "bike_ND.csv", and "bike_SF.csv" present cycling information on the three networks.
  	For each line, it contains the following information:
    		<link>: ID of the link
    		<origin>: origin of the link
    		<destination>: destination of the link
   		<cycling time>: Average cycling time on the link without a bike lane
  

Files "Small_Low_demand.csv", "Small_Med_demand.csv",  "Small_High_demand.csv", "NS_Low_demand.csv", "ND_Med_demand.csv",  "ND_High_demand.csv", 
"SF_Low_demand.csv", "SF_Med_demand.csv", and "SF_High_demand.csv" list three demand scenarios for each network. 
	For each line, it contains the following information:
    		<origin, destination, demand>: total travel demand between origin and destination nodes
   


Files "Small_Lane_cost.csv", "ND_Lane_cost.csv" and "SF_Lane_cost.csv" list the cost for builing a bike lane on each link in the three networks.
	For each line, it lists the cost for building a bike lane on the link. The link ID is equal to the row number.
  
 
Files "Small_Station_cost.csv", "ND_Station_cost.csv" and "SF_Station_cost.csv" list the cost for builing a bike station close to a node in the three networks.
	For each line, it lists the cost for building a bike station near the node whose ID is equal to the row number.
  
  
