### Issue Detection in High-Dimensional Time Series Data
As a Research Intern at Microsoft Research, India, I mainly worked on the following technique aimed towards building a real-time issue detection system in high-dimensional time-series data:
- **Sparse dictionary learning and sparse coding**^[1][2]^ - We experimented with appending the optimization objective (reconstruction error) with a term that induces **temporal dependency** between the successive sparse codes by penalizing on the distance between them.

Some other methods that we explored were:
- **Clustering on the subsets of attributes**^[3]^
- **Switching state-space models**^[4]^
- **Kalman filtering**
- **An approach based on KL-Divergence**

### Reasoning, Attetnion and Memory Based Machine Learning Models
For my bachelor's thesis, I explored two RAM based machine learning models - **Neural Turing Machines**^[6]^ and **End-to-End Memory Networks**^[6]^ with an aim to replicate both for a better practical understanding. I also worked on **Deep-Reinforcement Learning**^[7]^ and presented some ideas on combining two concepts to make agents (models) with more interpretable actions (predictions). Here are some useful links:
- [Project page](https://chiggum.github.io/Neural-Turing-Machines)
- [Thesis report](https://chiggum.github.io/Neural-Turing-Machines/Report/Report_MA499.pdf)
- [Presentation with comments](https://chiggum.github.io/Neural-Turing-Machines/presentation/ram_pres_with_notes.pdf)

### Real-Time Vectorization of Brain Atlases
I worked with [INCF](https://incf.org/) through [Google Summer of Code 2014](https://www.google-melange.com/archive/gsoc/2014) on building a real-time tracing software for vectorizing bitmaps of brain atlases. Our software outperformed other open source tracing softwares - AutoTrace and PoTrace, in terms of time complexity, generating accurate svg paths and visually aesthetic graphics without gaps or overlaps between regions. Here are some useful links:
- [Our tracing software page](https://chiggum.github.io/mindthegap)
- [Scalable Brain Atlas Template where this tracing software is being used](https://scalablebrainatlas.incf.org/macaque/DB09)

### Deterministic Finite Automata Membership Test in SIMT Environment
For a small-project of my parallel computing class, I implemented an algorithm^[9]^ for DFA membership test from scratch in CUDA with deployment on a Tesla K40. The algorithm involved a specialized partitioning of the input string into chunks so as to balance the workload on each thread and minimize latency. Here are some useful links:
- [Project Report](https://github.com/chiggum/HPC/tree/master/cuda/dfa_membership_test/Report.pdf)

### References
1. Mairal, J., Bach, F., Ponce, J., & Sapiro, G. (2010). Online learning for matrix factorization and sparse coding. Journal of Machine Learning Research, 11(Jan), 19-60.
2. Mairal, J., Bach, F., Ponce, J., & Sapiro, G. (2009, June). Online dictionary learning for sparse coding. In Proceedings of the 26th annual international conference on machine learning (pp. 689-696).
3. Friedman, J. H., & Meulman, J. J. (2004). Clustering objects on subsets of attributes (with discussion). Journal of the Royal Statistical Society: Series B (Statistical Methodology), 66(4), 815-849.
4. Ghahramani, Z., & Hinton, G. E. (2000). Variational learning for switching state-space models. Neural computation, 12(4), 831-864.
5. Graves, A., Wayne, G., & Danihelka, I. (2014). Neural turing machines. arXiv preprint arXiv:1410.5401.
6. Sukhbaatar, S., Weston, J., & Fergus, R. (2015). End-to-end memory networks. In Advances in neural information processing systems (pp. 2440-2448).
7. Mnih, V., Kavukcuoglu, K., Silver, D., Rusu, A. A., Veness, J., Bellemare, M. G., ... & Petersen, S. (2015). Human-level control through deep reinforcement learning. Nature, 518(7540), 529-533.
8. Ko, Y., Jung, M., Han, Y. S., & Burgstaller, B. (2014). A speculative parallel DFA membership test for multicore, SIMD and cloud computing environments. International Journal of Parallel Programming, 42(3), 456-489.
