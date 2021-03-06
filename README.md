# prng-sequence-guessing

### Task

Given a time range during which the Java Random generator was seeded and the last ten output values of random.nextInt(1000), guess the next value to be output by the generator.

### Input Format

The first line of input contains a number  indicating the number of test cases to follow. 
For each of the  test cases, a line will follow containing two space separated Unix timestamps representing the time during which the random number generator instance was created. The range between the two timestamps will be, at most, . 
The following ten lines contain the first ten numbers sequentially generated by the same Random instance's nextInt(1000) function, one on each line.

### Output Format

For each test case, output a line containing the seed used to create the generator and the next  integers that are output from random.nextInt(1000), separated by spaces.

### Sample Input
```
2
1374037200 1374123600
643
953
522
277
464
366
321
409
227
702
1374037299 1374143600
877
654
2
715
229
255
712
267
19
832
```
### Sample Output
```
1374037200 877 633 491 596 839 875 923 461 27 826
1374037459 101 966 573 339 784 718 949 934 62 368
```
