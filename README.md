Cognitive-Radios
================

A java program that sets up primary users arrival and secondary users arrival and work on spectrum allocation(Cognitive Radio Research-Work Program).

Here p.txt is file that is generated by markov chain analysis and is used for the program to read when the arrival and departure is. eg value at 0 tells arrival and value at 1 tells departure ans this (arrival-departure) goes on!!!

Now when the program starts then secondary users are asked to arrive so they follow a random pattern and they are nothing but packets.

Secondary user packets are assumed to be of short duration and during the Secondary user packet stay in queue if Primary user packet arrives then collision occurs and both have to be dropped (Collision count becomes +1);


