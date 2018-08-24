# MLAC
A SAC styled cluster of ML Algorithms instead of Analyzers.

Here, We will have many ML algorithms and a CORE FRAMEWORK which can run those algorithms.
This will be docker based aaplication. 

All algorithms have to be unit testable and function testable.
Unit tests and function tests will be carried out in the docker container.

docker compose and other stuffs will be used to run multiple algorithm containers parallely.

CORE framework will have a docker folder which will contain dockerfiles for
1) Algorithm itself
2) Algorithm Tester

Also, Core framework will have a config folder which contains configuration for each and every algorithm.
