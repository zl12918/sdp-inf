# sdp-inf
Example codes for our paper "..."

---------------------------------

The file Sp2_example.m contains MATLAB codes for obtaining the moment equations and moment matrices constraints, setting up constrained sets with these constraints via YALMIP, and optimising over the set to get bounds on parameters.

As an example, we implemented inference with two separate datasets from the 2-species model in our paper, each has a different unobserved species. For general use, one can easily modify the code to infer parameters with complete data or one partial data as well as other reaction networks.
