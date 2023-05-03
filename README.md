### Cassandra Cluster 
With this docker-compose file, you can create a cassandra cluster with 3 nodes.

# For CRUD operations at least 2 replica must be alive.



##Usage
In terminal type:

` docker-compose up -d `

Then:

` docker exec -it node<1/2/3> <command> `

To stop working:

` docker-compose down `

