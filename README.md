## Code used to generate figures 10- b,c,d of manuscript "Off-fault damage controls near-surface rupture behaviour in soft sediments" 

- The manucript is under review in Nature Communications as of Nov. 26, 2024. (reference number: NCOMMS-24-75893). Authors: Nicola De Paola, Rachael J. Bullock, Robert E. Holdsworth, Shmuel Marco, and Stefan Nielsen. 

- This code evaluates and plots analytical solutions that are described in the Methods of the manuscript.

- The coding is in Mathematica&copy; (Wolfram)
- It runs on Mathematica 13.2 (also most likely on any previous Mathematica release > 10, although I have not tested it)
- The conde runs in 18 seconds on a single thread / signle CPU of a computer with
  Architecture:                x86_64
  Processor:                   AuthenticAMD / AMD EPYC 7742 64-Core Processor

- Three versions are provided
  - Mathematica&copy; notebook
  - Mathematica&copy; .m file
  - Mathematica&copy; .pdf file (pdf version of the notebook)

- The code uses equations defined in the Manuscript, to calculate values of:
  - stress intensity
  - static fracture energy
  - energy flow as a function of rupture velocity
  - rupture velocity as a function of position
    
- Then the code plots the solution of velocity of rupture as a function of position on the fault for different scenarios

- Reproduction
  Reproduction of these graphics does not necessarily need Mathematica.
  Indeed this code essentially evaluates and plots analytical solutions that are described in the Methods of the manuscript.
  The plotting of the same solutions using the same parameter values can be reproduced with any common coding (e.g. python with numpy and matplotlib).
