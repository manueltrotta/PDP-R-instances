This is a description of the PDP-R benchmark instances from https://www.sciencedirect.com/science/article/pii/S0377221721006603. In every instance file there are four parameters and two sections, described below.

NUM_STATIONS: number of the stations on the ring.

NUM_REQUESTS: number of transportation requests.

NUM_VEHICLES: number of available vehicles.

VEHICLE_CAPACITY: capacity of the vehicle.

DISTANCES
In this section there is a line between any pair of stations. Every line is composed of 3 numbers and reports the distance between a pair of consecutive stations (i,i+1). The first two numbers denote stations, while the third number denotes the distance. So, for example, "0 1 4.5" means that the distance between stations 0 and 1 is 4.5.

REQUEST_SECTION
In this section there is a line for each request. Every line is composed of 5 numbers. The first two numbers denote the source and the target station of the request, respectively. The third and fourth number are the release and the due date associated with the request. The last number is the demand associated with the request.

The characters EOF denote the end of the file.
