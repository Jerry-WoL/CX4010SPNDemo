# CX4010 Project: Demonstration of Attacks on SPN Ciphers
Team member: Hu Zhuangyu, Li Ziyang

# #Overview
Construct a simple SPN implementation and apply linear cryptanalysis attack on the cipher to extract the key

# #Motivation
SPN cipher is a type of block cipher. It combines substitution boxes (s-box) and permutation boxes (p-box) for multiple rounds to achieve confusion and diffusion. A key scheduling algorithm is used to generate sub keys for each round of scrambling. Recovring the key is difficult even when both the plaintext and ciphertext are know (chosen plaintext attack). Linear cryptanalysis, first published by Mitsuru Matsui in 1992, is one of the two most important techniques in cryptanalysis (the other one is differential cryptanalysis).

# #Research & Design
We implement a simple SPN with 2 rounds of 4x4 bit S-boxes and 8 bit p-boxes. We implement the linear cryptanalysis with reference to a tutorial by Howard M. Heys (https://www.engr.mun.ca/~howard/PAPERS/ldc_tutorial.pdf) and a github repository (https://github.com/physics-sec/Linear-Cryptanalysis).

# #Development
All codes are written in one single python notebook with comments and markdowns.

# #Use of the Code
The codes may be used for cryptanalysis of SPN ciphers
