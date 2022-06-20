# Exploration of FUSE pipeline

Through the jupyter notebook contained in this repository I will explore the FUSE pipeline step by step. Each routine and subroutine will be tested seperately on some archival test data. The script closely follows the pipeline description by [Dixon et al. 2007](https://arxiv.org/pdf/0704.0899.pdf). 

The FUSE pipeline is written in C. The corresponding commands will be executed over a Python wrapper. The FUSE pipeline is very modular so each step can be executed seperately. The goal will be to simulate a flow from the raw data to the final data products. 
