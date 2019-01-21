NAME: HEERA SRIDHAR
UTA ID: 1001529609

Tower Of Hanoi:
The parts of the fact file that are common to all problems in this domain are:

(disk1 Object)
(disk2 Object)
(disk3 Object)
(disk4 Object)
(disk5 Object)
(A Object)
(B Object)
(C Object)

(preconds
(smaller disk1 disk2) (smaller disk1 disk3) (smaller disk1 disk4) (smaller disk1 disk5) (smaller disk2 disk3) (smaller disk2 disk4) (smaller disk2 disk5) (smaller disk3 disk4)
(smaller disk3 disk5) (smaller disk4 disk5) (smaller disk1 A) (smaller disk1 B) (smaller disk1 C) (smaller disk2 A) (smaller disk2 B) (smaller disk2 C) (smaller disk3 A)
(smaller disk3 B) (smaller disk3 C) (smaller disk4 A) (smaller disk4 B) (smaller disk4 C) (smaller disk5 A) (smaller disk5 B) (smaller disk5 C))

Here A,B,C represents the 3 pegs and disk1,disk2,disk3,disk4,disk5 represents the 5 disks.

(smaller disk1 disk2) interprets that disk1 is smaller than disk2.

7-puzzle problem:

The parts of the fact file that are common to all problems in this domain are:

(1 Object)
(2 Object)
(3 Object)
(4 Object)
(5 Object)
(6 Object)
(7 Object)
(B11 Object)
(B12 Object)
(B13 Object)
(B21 Object)
(B22 Object)
(B23 Object)
(B31 Object)
(B32 Object)
(B33 Object)

(preconds
 (adjacent B11 B12) (adjacent B11 B21) (adjacent B12 B11) (adjacent B12 B13) (adjacent B12 B22) (adjacent B13 B12) (adjacent B13 B23) (adjacent B21 B11) (adjacent B21 B22) (adjacent B21 B31) (adjacent B22 B21) (adjacent B22 B12) (adjacent B22 B23) (adjacent B22 B32) (adjacent B23 B22) (adjacent B23 B33) (adjacent B23 B13) (adjacent B31 B21) (adjacent B31 B32) (adjacent B32 B31) (adjacent B32 B33) (adjacent B32 B22) (adjacent B33 B32) (adjacent B33 B23))


Here B represents a block and the 7-puzzle is visualized in this 3x3 matrix format:

                                                                     B11     B12   B13
                                                                     
                                                                     B21     B22   B23
                                                               
                                                                     B31     B32   B33

Here (adjacent B11 B12) means block11 has block12 as its neighbour. So if we look at the puzzle B11 neighbours are B12,B21. Similarly its written for all other blocks.
















