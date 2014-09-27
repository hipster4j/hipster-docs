<center>![logo](images/hipster-logo-big.png)</center>

# Hipster - version 1.0.0-rc1

Welcome to Hipster - an open-source java library for Heuristic Search. The aim of Hipster is to provide an easy to use yet powerful and flexible type-safe Java library for heuristic search. Hipster relies on a flexible model with generic operators that allow you to reuse and change the behavior of the algorithms very easily. Algorithms are also implemented in an iterative way, avoiding recursion. This has many benefits: full control over the search, access to the internals at runtime or a better and clear scale-out for large search spaces using the heap memory.

You can use Hipster to solve from simple graph search problems to more advanced state-space search problems where the state space is complex and weights are not just double values but custom defined costs.

## Why Hipster?

Surprisingy, there is a lack of Java libraries that implement search algorithms with an extensible, flexible and simple to use model. In fact, most of the libraries rely on graph structures or recursive implementations which do not offer fine-grained control over the algorithm. It is very common to find many projects (such as graph libraries, noSQL databasest, etc) reinventing the wheel each time they need to use a common search algorithm to solve a concrete problem.

Hipster aims to solve this problem by providing the common components of a search algorithm.

## Hipster License

Hipster is licensed under the Apache 2 license. In a few words, this license allows you to use this library (or any modification of it) for both personal or commercial projects:


    Copyright 2013 Centro de Investigación en Tecnoloxías da Información (CITIUS),
    University of Santiago de Compostela (USC).

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.

