# Machine-Learning
Explorations in quantum ML

## Frank Zickert
Look in my [Learning Exercises)](https://github.com/rfryeSigma/Learning_Excercises) repository for `Jupyter` notebooks for exercises related to chapters of
```
    Hands-On Quantum Machine Learning With Python
    Volume 1: Get Started by Dr. Frank Zickert
    Copyright © 2021 Dr. Frank Zickert, pyqml.com
```

## Other Quantum ML Books

When I find the time I will have much to say about these books:

#### Maria Schuld
```
    Machine Learning with Quantum Computers
    By Maria Schuld and Francesco Petruccione
    Springer (2nd edition 2021), 312 pages
```

#### Peter Wittek
```
    Quantum Machine Learning
    What Quantum Computing Means to Data Mining
    By Peter Wittek
    Elsevier AP, Academic Press (2014), 163 pages
```

#### Kristof Schütt
```
    Machine Learning Meets Quantum Physics
    Edited by Kristof T. Schütt, Stefan Chmiela, O. Anatole von Lilienfeld, Alexandre Tkatchenko, Koji Tsuda, Klaus-Robert Müller
    Springer Lecture Notes in Physics (2020), 467 pages
````

#### Santanu Ganuly
```
    Quantum Machine Learning: An Applied Approach
    The Theory and Application of Quantum Machine Learning in Science and Industry
    By Santanu Ganguly
    Apress (2021)
````

#### Davide Pastorello
```
    Quantum Chemistry in the Age of Machine Learning
    By Davide Pastorello
    Springer (2022), 138 pages
````

#### Pavlo O. Dral
```
    Quantum Chemistry in the Age of Machine Learning
    By Pavlo O. Dral
    Elsevier (2023), 682 pages
````

#### Siddhartha Bhattacharyya
```
    Quantum Machine Learning
    Edited by Siddhartha Bhattacharyya, Indrajit Pan, Ashish Mani, Sourav De, Elizabeth Behrman, Susanta Chakraborti
    Walter de Gruyter (2020), 118 pages
````

## Quantum Reservoir Computing
I believe that noisy random quantum sub-circuits can be trained to recognize input and output patterns for quantum circuits.

I am experimenting with this idea, but nothing to show yet. Here are some links on the subject:
- [Wiki page Reservoir_computing](https://en.wikipedia.org/wiki/Reservoir_computing)
- [Nature article on external reservoir](https://www.nature.com/articles/s41598-022-05061-w)
- [arxiv: Optimal quantum reservoir computing for the NISQ era](https://arxiv.org/abs/2205.10107)
- [arxiv: Reservoir Computing via Quantum Recurrent Neural Networks](https://arxiv.org/abs/2211.02612)

More papers and some code:

#### Domingo
```
    L. Domingo, G. Carlo, and F. Borondo
    Optimal quantum reservoir computing for the NISQ era
```

[arxiv](https://arxiv.org/pdf/2205.10107.pdf), 5/2022, 6 pages

They find optimal gates for QRC better than Ising.
I wonder whether circuits decayed after a dozen circuit steps.
Compare gate complexity by majorization.
[Source code](https://github.com/laiadc/Optimal_QRC)

#### Burgess
```
    Adam Burgess and Marian Florescu
    Quantum Reservoir Computing Implementations for Classical and Quantum Problems
```

[arxiv](https://arxiv.org/pdf/2211.08567.pdf)

They use a quantum physical reservoir ahead of a RNN.

#### Fujii
```
    Keisuke Fujii and Kohei Nakajima
    Quantum reservoir computing: a reservoir approach toward quantum machine learning on near-term quantum devices
```

[arxiv](https://arxiv.org/pdf/2011.04890.pdf), 11/2020, 13 pages

More proof of concept of physical reservoir than implementation.

#### Chen
```
    Jiayin Chen, Hendra I. Nurdin, and Naoki Yamamoto
    Temporal information processing on noisy quantum computers
```

[arxiv](https://arxiv.org/pdf/2001.09498.pdf), 7/2020, 22 pages

Proof of principal on IBM 5 qubit machines.

#### Suzuki
```
    Yudai Suzuki, Qi Gao, Ken C. Pradel, Kenji Yasuoka & Naoki Yamamoto
    Natural quantum reservoir computing for temporal information processing
```

[Nature article](https://www.nature.com/articles/s41598-022-05061-w), 1/2022

Uses natural noise of each QC config. Time series and classify.
Better QRC gates and more shots needed for better stats.

#### Angelatos
```
    Gerasimos Angelatos Sae,ed A. Khan, and Hakan E. Türeci
    Reservoir Computing Approach to Quantum State Measurement
```

[PhysRevX article](https://journals.aps.org/prx/pdf/10.1103/PhysRevX.11.041062), 12/2021, 18 pages

[Princeton Thesis lecture](https://ece.princeton.edu/events/reservoir-computing-and-quantum-systems)

```
    Saeed A. Khan, Fangjun Hu, Gerasimos Angelatos, and Hakan E. Tureci
    Physical reservoir computing using finitely-sampled quantum systems
```

[arxiv](https://arxiv.org/pdf/2110.13849.pdf), 11/2021, 38 pages

Recommends use QC as reservoir, or use reservoir to improve circuit readout.

In these videos, Angelatos uses external oscillators in the fridge as reservoir for speed.

[A Reservoir Computing Approach to Quantum State Measurement](https://www.youtube.com/watch?v=HHXMkjTAuqg&t=53s)

[Kerr Network Reservoir Computing for Quantum State Measurement](https://www.youtube.com/watch?v=WKFda_1KcMw)
