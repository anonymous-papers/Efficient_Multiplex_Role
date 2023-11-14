# Efficient_Multiplex_Role
Code for paper "Enhancing Network Role Modeling: Introducing Attributed Multiplex Structural Role Embedding for Complex Networks"
How to use:

Our model: src/models/AE.py

vis_barbell.py     embedding visualization on multiplex barbell graph

house.py 
house_p.py
varied.py
varied_p.py        node clustering and classification experiments on synthetic graphs 



Code reference:

This code is built upon the code of the following papers:

Claire Donnat, Marinka Zitnik, David Hallac, and Jure Leskovec. "Learning Structural Node Embeddings via Diffusion Wavelets." KDD 2018. https://github.com/snap-stanford/graphwave

Jiao, Pengfei, Xuan Guo, Ting Pan, Wang Zhang, Yulong Pei, and Lin Pan. "A survey on role-oriented network embedding." IEEE Transactions on Big Data 8, no. 4 (2021): 933-952.


The Twitter network is removed from the data since it needs 2GB of space, and must be anonymized first. Our code and data will be made public available after review.
