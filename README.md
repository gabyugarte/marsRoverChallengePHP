# marsRoverChallengePHP

==========

Description
==========
Your Task You’re part of the team that explores Mars by sending remotely controlled vehicles to the surface of the planet. Develop a software that translates the commands sent from earth to instructions that are understood by the rover. Requirements

● You are given the initial starting point (x,y) of a rover and the direction (N,S,E,W) it is facing. ● The rover receives a collection of commands. (E.g.) FFRRFFFRL ● The rover can move forward (f). ● The rover can move left/right (l,r). ● Suppose we are on a really weird planet that is square. 200x200 for example :) ● Implement obstacle detection before each move to a new square. If a given sequence of commands encounters an obstacle, the rover moves up to the last possible point, aborts the sequence and reports the obstacle.

Take into account

● Rovers are expensive, make sure the software works as expected.

Test
==========
To run the tests just run:

```
./vendor/bin/phpunit

```
You need PHP 5.6 or above to run it since we have phpunit 5.2.

If you have legacy version of php please change composer.json file
and include the version that is compatible with you version of PHP

If you change the phpunit version do not forget to run:

```
./composer update --with-dependencies

```
