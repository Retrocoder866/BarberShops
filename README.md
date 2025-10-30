A "barber shop game for an operating system" is not a commercial video game but an educational project used to demonstrate fundamental concepts of concurrent programming and process synchronization. The simulation, known as the Sleeping Barber Problem, is a classic exercise in computer science for showing how to manage threads and prevent issues like deadlock and race conditions. 
The basic scenario for the game/simulation is as follows:
There is a single barber who can serve one customer at a time.
There is a waiting room with a fixed number of chairs for customers.
If a customer arrives and the barber is busy, they wait in a free chair. If all waiting chairs are full, the customer leaves.
If a customer arrives and the barber is sleeping, they wake the barber.
If the barber finishes a haircut and there are no customers waiting, the barber goes to sleep. 
