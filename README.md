# MAC-address-derandomization

Steps:

1- Use the same dataset of the lecture to implement an online clustering technique for probe requests

2- At every received (read) probe request, two options are available:
Create a new cluster
Assign the probe to an existing cluster

3- Decision is made based on a feature similarity metric:
A probe is assigned to an existing cluster if at least N of its features match the ones of the cluster (no matter what features). Resolve ties as you prefer (e.g. first match wins)

4- You should test different N and select the one that maximizes the cluster performance (v-measure and error). 

5- Now validate your approach on the new dataset in the challenge-dataset folder, which contains 6 new labeled devices

6- Validation should be performed at different test-set size K

E.g.: for K = 2, create 5 new different test-sets composed of 2 randomly selected devices. Test the approach on the five test sets and report punctual and average performance. Do the same for K=3…5 (only 1 test set of K=6 is possible).

7- Plot average performance measures of the 5 test sets vs K and comment the result

8- Run your best technique on the new (unlabeled) provided dataset unlabelled-challenge.csv and estimate the number of devices

This repository contains in class activites for the course "Network Measurement and Data Analysis", taught by [Prof. Redondi](https://scholar.google.com/citations?user=8ka5NmUAAAAJ&hl=en) and [Prof. Musumeci](https://scholar.google.it/citations?user=RsM0KB0AAAAJ&hl=it) at Politecnico di Milano.

