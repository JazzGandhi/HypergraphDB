# HypergraphDB Basics
 
HyperGraphDB is a storage framework based on generalized hypergraphs as its underlying data model. The unit of storage is a tuple made up of 0 or more other tuples. Each such tuple is called an atom.

This repository contains the basic implementation of some of the HypergraphDB's features

It contains the following implementations in the following respective files:
1) Add Nodes in HypergraphDB - AddAuthor.java
2) Remove Nodes from HypergraphDB - removeAuthor.java
3) Viewing all the Nodes of a specific class - ViewAllHandles.java
4) Creating Links between different nodes and finding the link's arity - CreateLinks.java

Note:
Normal graphs have the link parity of 2. The special feature of HypergraphDB is that a link can have any arity that we want.

Official docs : http://hypergraphdb.org/