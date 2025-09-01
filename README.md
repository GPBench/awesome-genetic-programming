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
- GE: Grammatical Evolution
  
## Table of Contents

<!-- MarkdownTOC depth=4 -->
<!-- Contents-->
- [Awesome Genetic Programming](#awesome-genetic-programming)
  - [Algorithm implementations](#algorithm)
    - [Boolean function synthesis](#boolean-function-softwares)
      
    - [Symbolic Regression](#sybolic-reggression-softwares)
      - **[pyCGP](https://github.com/scussatb/pyCGP)** (CGP): Python implementation focused on symbolic regression and image analysis
      - **[cartesian](https://github.com/Ohjeah/cartesian)** (CGP): Lightweight Python CGP for symbolic regression
      - **[dcgp](https://github.com/darioizzo/dcgp)** (CGP): Differentiable CGP with derivative information for advanced optimization
      - **[operon](https://github.com/heal-research/pyoperon)** (TGP): a high-performant Python library with a C++ backend
      - **[pysr](https://github.com/MilesCranmer/PySR)** (TGP): customizable Python library with a Julia backend
      - **[eggp](https://github.com/folivetti/eggp)** (TGP): search-efficient symbolic regression based on e-graphs with a Haskell backend
      - **[gp-gomea](https://github.com/marcovirgolin/GP-GOMEA)** (TGP): implementation focused on finding simpler models without hurting accuracy
      - **[gpg](https://github.com/marcovirgolin/gpg)** (TGP): new implementation of GP-GOMEA focused solely on symbolic regression
      - **[brush](https://github.com/cavalab/brush)** (TGP): interpretable machine learning library for training symbolic models mixing decision trees with mathematical models.
      - **[bingo](https://github.com/nasa/bingo)** (TGP): symbolic regression incorporating uncertainty information through Bayesian approaches.
    - [Reinforcement Learning](#reinforcement-learning-softwares)
      - **[CartesianGeneticProgramming.jl](https://github.com/d9w/CartesianGeneticProgramming.jl)**: Julia implementation based on Cambrian.jl framework
      - **[gpFlappyBird](https://github.com/ShuhuaGao/gpFlappyBird)**: CGP trained to play Flappy Bird
    - [Program Synthesis](#program-synthesis-softwares)
      - **[MAGE.jl](https://github.com/camilodlt/MAGE.jl)**: Multimodal Adaptive Graph Evolution, a typed extension of CGP
    - [Machine learning](#machine-learning-softwares)
      - **[CGPNAS](https://github.com/Cosijopiii/CGPNAS)**: CGP for multi-objective neural architecture search
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

### Boolean Function Softwares

- **[cgp-plusplus](https://github.com/RomanKalkreuth/cgp-plusplus)** (CGP): Modern C++ implementation with concurrency, checkpointing, and benchmarks
