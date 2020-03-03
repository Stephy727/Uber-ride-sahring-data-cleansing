# Uber-ride-sharing-data-cleansing

The dataset is about Uber Ridesharing data in Victoria, Australia . The description of each data

Id - A unique id for the journey

Uber type -  A categorical attribute for the type of the journey namely Uber pool, Uberx, Uber black. All we know is that the cost of these types of journeys may be different.

Origin region - A categorical attribute representing the region for the origin of the journey

Destination region - A categorical attribute representing the region for the destination of the journey

Origin latitude - Latitude of the origin coming from nodes.csv file

Origin longitude - Longitude of the origin coming from nodes.csv file

Destination latitude - Latitude of the destination coming from nodes.csv file

Destination longitude - Longitude of the destination coming from the nodes.csv file

Journey Distance - The shortest path, in meters, between the origin and the destination with respect to the nodes.txt and the edges.txt files.

Dijkstra algorithm can be used to find the shortest path between two nodes in a graph. Reading materials can be found here .

Departure date - Date of the departure. We know that the price is different on weekdays compared to weekends.

Departure time - Time of the departure. We know that the Uber company has a specific rule to define a discrete number for morning (i.e. 0) (6:00:00 - 11:59:59), afternoon (i.e. 1) (12:00:00 - 20:59:59), and night (i.e. 2) (21:00 - 5:59:59) to calculate the fare.

Travel time - Travel time (i.e., duration) of the journey in seconds. Note that road types have their own speed limit in the edges.csv file and the car always travel with the exact speed limit.

Arrival time - The time of the arrival

Fare$ - The fare of the journey. We know that the fare has a linear relation with some of the attributes of the dataset.

The syntactic, semantic, and coverage errors have been corrected. Details are all mentioned in the Jupyter file
