# Functional-composition

Solving programming problems using functional composition 

## Description

This was a university project developed in haskell for the code development and latex to documentation and pdf generator.

## Usage

To run this project we use a docker container, to create the docker container we use: ```docker build -t cp2324t``` and then ```docker run -v ${PWD}:/cp2324 -it cp2324t```

When inside the docker container we can build the project repor using a simple `make`

To run the haskell module, just run ```ghci cp2324t.lhs```