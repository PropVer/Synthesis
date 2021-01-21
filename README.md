# Synthesis
The objective of this project is to enable automated synthesis and verification of parameterized distributed systems through a topology and property-specific fashion. The underlying hypothesis of this work is as follows:

Developing property and topology-specific algorithms for the verification and synthesis of parameterized distributed programs/protocols significantly facilitates the verification and synthesis of parameterized protocols with arbitrary topology and for general case temporal properties specified in Linear Temporal Logic (LTL).

Such a property and topology-specific method will result in a repository of algorithms and tools that generate parameterized protocols on elementary topologies such as ting, tree, line, mesh, etc. The focus of this project is on developing such a repository. A related project focuses on discovering rules and theorems for composing parameterized protocols on elementary topologies towards generating parameterized protocols that satisfy LTL properties on more complicated and compositional topologies. As the first step of this project, we have implemented a synthesis algorithm for the synthesis of symmetric uni-directional rings that satisfy leadsto properties. A leadsto property captures the eventual response of the entire ring to some global stimilus.

Installation instruction:

1- Download the source file

2- Copy espresso-ab-1.0-master.zip from the source file into root of program file and make it unzip

3- Install espresso:

 3.1 - ./configure
 
 3.2 - make
 
4- Install and run the program:

 4.1 -  g++  *.cpp -I.  -o SynLeadsTo  -ldl
 
 4.2 -  ./SynLeadsTo 
