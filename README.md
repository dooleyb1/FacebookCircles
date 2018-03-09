# FacebookCircles
Java program that uses a Facebook supplied data set to compute friendship statistics. 

This program uses actual (anonymised) Facebook data, obtained from the [SLN Dataset](http://snap.stanford.edu/data/index.html).

A Facebook friendship is an undirected relationship between two people. In this assignment we will consider that "my friend's friend is my friend"; i.e., that the friendship relationship is **transitive**. A Facebook user's circle of friends is the largest set of her friends. Note that two facebook users who are friends have the same circle of friends.

## Methods 

+ **public FacebookCircles(int numberOfFacebookUsers):** the constructor creates a new object of the class initialised to a fixed number of facebook users. Each user will be represented by an integer from 0 to numberOfFacebookUsers - 1.

+ **public void friends( int user1, int user2 ):** Declares that two users are friends.

+ **public int numberOfCircles():** Returns the number of friendship circles.

+ **public int sizeOfLargestCircle():** Returns the size of the the largest friendship circle.

+ **public int sizeOfAverageCircle():** Returns the average size of the friendship circles. The average should be computed as (s1 + s2 + ... + sn) /n, where "/" is integer division.

+ **public int sizeOfSmallestCircle():** Returns the size of the smallest friendship circle.