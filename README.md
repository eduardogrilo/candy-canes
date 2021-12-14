Candy canes distribution
This code is part of the "Tech Challenge Series – Advent Calendar 2021" advanced by Blip.pt (developed by Devskiller).

*This year counting down to Christmas will be even funnier and Blip will be by your side the whole time with a variety of small programming puzzles and lots of prizes!*

## Task description
To congratulate the Elf's good work in the Christmas factory, Santa brought to the factory a bag full of packets with candy canes.  
Each packet of candy canes has a variable amount of candies inside.  

Santa wants to give a unique packet to each Elf, but being as fair as possible.  
Calculate the minimum possible difference between maximum number of candies given to an Elf and minimum number of candies given to an Elf  

**Function signature**  
findMinDiff(int[] packets, int numberOfElfs) returns int

**Examples:**
numberOfElfs = 5  
packets = {4, 5, 2, 10, 57, 8, 10, 13}  
Result: 6  

The minimum difference between maximum candies and minimum candies is 10 - 4 = 6 by choosing the following packets: {4, 5, 10, 8, 10}.  

**Constraints**  
number of packets is between 0 and 100 000   
number of Elfs is between 0 and number of packets  
number of candies in a packet is between 0 and 1 000 000 000
