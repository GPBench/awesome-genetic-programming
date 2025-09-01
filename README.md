# Awesome Genetic Programming

A curated list of awesome genetic programming books, papers, tutorials, conferences, and softwares (by language).

Contribute to this list sending a pull request and help identifying deprecated content. Deprecations should be marked if:

- The repostory explicitly mention it.
- +5 years without commit.

Deprecated software will still be maintained in the list according to popularity.

Some usefule acronyms:

- TGP: Tree-based Genetic Programming
- CGP: Cartesian-Graph Genetic Programming
- LGP: Linear Genetic Programming
- GE: Grammatical Evolution or grammar based Genetic Programming
  
## Table of Contents

<!-- MarkdownTOC depth=4 -->
<!-- Contents-->
- [Awesome Genetic Programming](#awesome-genetic-programming)
  - [Algorithm implementations](#algorithm)
    - [Boolean function synthesis](#boolean-function-algorithms)      
    - [Symbolic Regression](#symbolic-reggression-algorithms)
    - [Reinforcement Learning](#reinforcement-learning-algorithms)      
    - [Program Synthesis](#program-synthesis-algorithms)
    - [Machine learning](#machine-learning-algorithms)
    - [Multi domain and Multiple Representation](#multi-domain-and-multiple-representation)
    - [Utility tools and libraries](#general-tools)
  - [Benchmarks](#benchmarks)
    - [General Boolean Synthesis](#general-boolean-synthesis)
    - [Symbolic Regression Benchmark (SRBench)](#srbench)
    - [Feynman equations](#feynman)
    - [Program Synthesis Benchmark](#psb1)
    - [Program Synthesis Benchmark 2](#psb2)
    - [ARC Challenge](#arc-challenge)
  - [Datasets](#datasets)
    - [PMLB](#pmbl)
    - [OpenML](#openml)
  - [Books](#books)
  - [Tutorials](#tutorials)
    - **[CGP tutorial](https://github.com/d9w/CGP-tutorial)**: 2025 GECCO tutorial on Cartesian Genetic Programming
  - [Courses](#courses)
    - **[ISAE-Supaero Evolution class](https://github.com/d9w/evolution)**: module on evolution with a class on GP
  - [Papers](#papers)
  - [Researchers](#researchers)

## Algorithm

### Boolean Function Algorithms

#### CGP

- **[cgp-plusplus](https://github.com/RomanKalkreuth/cgp-plusplus)**: Modern C++ implementation with concurrency, checkpointing, and benchmarks

### Symbolic Reggression Algorithms

#### CGP

- **[pyCGP](https://github.com/scussatb/pyCGP)**: Python implementation focused on symbolic regression and image analysis
- **[cartesian](https://github.com/Ohjeah/cartesian)**: Lightweight Python CGP for symbolic regression
- **[dcgp](https://github.com/darioizzo/dcgp)**: Differentiable CGP with derivative information for advanced optimization

#### TGP

- **[operon](https://github.com/heal-research/pyoperon)**: a high-performant Python library with a C++ backend
- **[pysr](https://github.com/MilesCranmer/PySR)**: customizable Python library with a Julia backend
- **[eggp](https://github.com/folivetti/eggp)**: search-efficient symbolic regression based on e-graphs with a Haskell backend
- **[gp-gomea](https://github.com/marcovirgolin/GP-GOMEA)**: implementation focused on finding simpler models without hurting accuracy
- **[gpg](https://github.com/marcovirgolin/gpg)**: new implementation of GP-GOMEA focused solely on symbolic regression
- **[brush](https://github.com/cavalab/brush)**: interpretable machine learning library for training symbolic models mixing decision trees with mathematical models.
- **[bingo](https://github.com/nasa/bingo)**: symbolic regression incorporating uncertainty information through Bayesian approaches.

### Reinforcement Learning Algorithms

#### CGP

- **[CartesianGeneticProgramming.jl](https://github.com/d9w/CartesianGeneticProgramming.jl)**: Julia implementation based on Cambrian.jl framework
- **[gpFlappyBird](https://github.com/ShuhuaGao/gpFlappyBird)**: CGP trained to play Flappy Bird

#### LGP

- **[](https://github.com/giorgia-nadizar/cgpax)**: LGP and CGP implementation with BRAX/JAX.

### Program Synthesis Algorithms 

#### CGP

- **[MAGE.jl](https://github.com/camilodlt/MAGE.jl)**: Multimodal Adaptive Graph Evolution, a typed extension of CGP

#### TGP

- **[hotGP](https://github.com/mcf1110/hotgp)**: higher-order typed genetic programming
- **[origami](https://github.com/mcf1110/origami)**: genetic programming evolving recursion schemes

#### Stack

- **[pushgp](https://github.com/lspector/Clojush)**: Push-GP, a stack-based genetic programming for program synthesis

#### GE 

- **[g3p](https://robert-haas.github.io/g3p/)**: grammar-guided genetic programming
- **[cbgp](https://github.com/erp12/cbgp-lite)**: Code Building Genetic Programming for a narrow subset of the Clojure language.

### Machine Learning Algorithms

#### CGP 
- **[CGPNAS](https://github.com/Cosijopiii/CGPNAS)**: CGP for multi-objective neural architecture search
- **[NEAT](https://nn.cs.utexas.edu/soft-view.php?SoftID=4)**: Neuroevolution of augmenting topologies
- **[HyperNEAT](https://github.com/SirBob01/HyperNEAT)**: Hypercube-based NEAT

### Multi domain and Multiple Representation

- **[tinyverseGP](https://github.com/gpbench/tinyversegp)**: minimalist implementation of multiple representations for multiple problem domains.
- **[geneticengine](https://github.com/alcides/GeneticEngine)**: search-based Python library that allows you to describe the structure of your solutions as Python dataclasses and abstract classes, and explores the solution space using different algorithms, such as enumerative search, hill climbing, and several flavors of Genetic Programming.

### General Tools

- **[rEGGression](https://github.com/folivetti/reggression)**:  an interactive tool that can help SR users to explore alternative models generated from different sources. These sources can be: the final population of a single run, the Pareto front, the entire history of visited expressions during the search, or a combination of those sources from multiple runs of the same or different algorithms

## Benchmarks

### [General Boolean Synthesis](https://github.com/boolean-function-benchmarks/benchmarks)

### SRBench

### Feynman

### PSB1

### PSB2

### ARC Challenge

## Datasets

## Books

## Tutorials

## Courses

## Papers

## Researchers
