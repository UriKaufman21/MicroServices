# Example of API
1. 2 Microservices, you can sent a post request for him to process something and return it
2. 1 Service that will send something to service 1 get the output, send to service 2
3. For now, no need for advanced logging and stuff
4. One microservice will generate random vector in a length that you specifi as an argument
5. The second will get a vector and will return the sum of its elements
6. Advanced, the first microservice will get a length, generate a string, save it to DB, the second will get the vector ID, get it from the DB and process it.