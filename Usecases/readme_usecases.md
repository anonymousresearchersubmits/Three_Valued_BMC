# Usecases for the three-valued BMC

Illustration of the use cases.

## Traffic light
Automaton that models a traffic light for pedestrian crossing.
The states are expressed as integers.
Each state is a touple of colours of the traffic lights for cars and pedestrians.
Transitions are times with internal counters and an universal counter.
Needs to be made framework compatible

## Spring-mass system
Spring-mass system with saturation to the controller's input, and a PID.
Same system used as case study for RV26
Needs to be made framework compatible

## car_follower_SSTL_mon_RV26
A follower car that needs to maintain safe distance from the leader car, which breaks abruptly.
In the original file are also the specification and the nodes for monitoring.
By Kenwright, Logan, et al. "Synchronous Observers Revisited for Runtime Verification of Lustre Using STL." International Conference on Runtime Verification. Cham: Springer Nature Switzerland, 2026.
