# poisson process
For research or simulation purposes, poisson is often used.
This is a simple example that generates the poisson process with python
. More directly, it generatesthe timings of every poisson event(e.g. the timings of vehicles' arrivasl
at a intersection)

After get the timings, they should be input to your simulator.(e.g. NS-3 .etc)


how to generate poisson procee ?

first thing you have to understand the differences bettwen poisson ditribution and possion process ?
several anwers in stackflow helped a lot
http://stackoverflow.com/questions/1155539/how-do-i-generate-a-poisson-process/10250877#10250877
http://stackoverflow.com/questions/5148635/how-to-simulate-poisson-arrival
http://ja.pymotw.com/2/random/

pyhthon has its own function to generate possion process by using the relationship between exponential distribution and poisson distribution.
