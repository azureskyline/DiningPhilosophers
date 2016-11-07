# DiningPhilosophers

The dining philosopher’s problem
This concept is associated with the classic concurrency problem dealing with synchronization. In the problem there are five philosophers who are concerned with thinking, becoming hungry and eating. The problem is that although each philosopher has one chopstick, they all have to eat with a shared chopstick without risking starvation. And so the process would be for one philosopher to pick up the chopstick and then eat, then put down or return the chopstick to let other philosophers eat.


# The Monitor solution – server class
The use of the monitor is to observe all the states of the philosopher and make sure that every one of the philosophers (zenyattas) will be able to eat. 

For this the project uses the lock, reentrantlock and condition classes in java 8 to achieve making the monitor class (for the project’s purpose is called the server).

# Philosophers class
This class’s job is to constantly make the philosopher do three actions which is:
Think		hungry		eat 
At the beginning of the program the philosopher is set to think.

# Driver class
This class initializes the philosophers and the monitor-server. It constantly loops to allow infinite executions.
