This code generates the figures from the paper "Kelly Bets and Single-Letter Codes: Optimal Information Processing in Natural Systems" by Alex Moffett and Andrew Eckford.

Live versions of these notebooks can be run on Google Colab:
[Figure 2](https://colab.research.google.com/drive/1syIE324aByM53txRKkpb2qdMue1VKA9e)
[Figure 3](https://colab.research.google.com/drive/1N_r3_T1Qz8Wm2B8RygRmOTo4Rpy0Vhz4)
[Figure 4](https://colab.research.google.com/drive/1mu_5IUbuCDsVlfoi_xJA33_oZUnVD3yu)

The code both generates and plots the curves. Thus, curves can be generated for arbitrary parameters.

The module RateDistortion.py contains useful functions for generating R(D) curves. Functions are provided which implement both the Blahut-Arimoto algorithm, as well as an EM-based algorithm [1]. Blahut-Arimoto is faster, but the EM-based algorithm has better convergence properties, and is used to generate all results in the notebooks.

[1] M. Hayashi, "Bregman divergence based em algorithm and its application to classical and quantum rate distortion theory," IEEE Transactions on Information Theory, vol. 69, no. 6, pp. 3460–3492, 2023.

