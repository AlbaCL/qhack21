# Q-Hack 2021

This is a repository with some code examples to get a gentle introduction to classical data encoding in quantum circuits and how to use it to construct a variational quantum classifier, a function fitter and to learn energy profiles of Hamiltonians.
It is the complementary material from my [Q-Hack 2021](https://qhack.ai/index.html) presentation (you can find the [slides here](https://albacl.github.io/files/QHack2021.pdf) and the [recording here](https://www.twitch.tv/videos/920118091)).

You will need to install `Tequila`[1] to run the notebook and play with them. 

- [Download and installation instructions](https://github.com/aspuru-guzik-group/tequila). 
- [Tutorials](https://github.com/aspuru-guzik-group/tequila-tutorials).
- [Overview video](https://www.youtube.com/watch?v=hUdf0P2fW2E) or [this one](https://www.youtube.com/watch?v=eUqUUAUFHyc).

If you want to learn about Variational Quantum Algorithms and Noisy Intermediate-Scale Quantum (NISQ) computing, you can check the review [2].

## Content

- [Single-qubit classifier](https://github.com/AlbaCL/qhack21/blob/main/SingleQubitClassifier.ipynb) [3]
- [Meta-Variational Quantum Eigensolver for spin chains](https://github.com/AlbaCL/qhack21/blob/main/Meta-VQE.ipynb) [4]
- [Meta-VQE for chemistry](https://github.com/AlbaCL/qhack21/blob/main/Molecular-Meta-VQE.ipynb) [4]
- [Quantum function fitter](https://github.com/AlbaCL/qhack21/blob/main/QFit.ipynb) [5,6]

The Meta-VQE notebook come from [this repository](https://github.com/aspuru-guzik-group/meta-vqe).


## References

[1] _Tequila: A platform for rapid development of quantum algorithms_, <br/>
J. S. Kottmann, S. Alperin-Lea, T. Tamayo-Mendoza, A. Cervera-Lierta, C. Lavigne, T.-C. Yen, V. Verteletskyi, P. Schleich, A. Anand, M. Degroote, S. Chaney, M. Kesibi, N. Grace Curnow, B. Solo, G. Tsilimigkounakis, C. Zendejas-Morales, A. F. Izmaylov, A. Aspuru-Guzik, <br/>[Quantum Science and Technology](https://iopscience.iop.org/article/10.1088/2058-9565/abe567/pdf), [arXiv:2011.03057 [quant-ph]](https://arxiv.org/abs/2011.03057).

[2] _Noisy intermediate-scale quantum (NISQ) algorithms_, <br/>
K. Bharti, A. Cervera-Lierta, T. H. Kyaw, T. Haug, S. Alperin-Lea, A. Anand, M. Degroote, H. Heimonen, J. S. Kottmann, T. Menke, W.-K. Mok, S. Sim, L.-C. Kwek, A. Aspuru-Guzik, <br/>
[arXiv:2101.08448 [quant-ph]](https://arxiv.org/abs/2101.08448) (2021).

[3] _Data re-uploading for a universal quantum classifier_, <br/>
A. Pérez-Salinas, A. Cervera-Lierta, E. Gil-Fuster, J. I. Latorre, <br/>
[Quantum 4, 226 (2020)](https://quantum-journal.org/papers/q-2020-02-06-226/).

[4] _The Meta-Variational Quantum Eigensolver (Meta-VQE): Learning energy profiles of parameterized Hamiltonians for quantum simulation_,<br/>
A. Cervera-Lierta, J. S. Kottmann, A. Aspuru-Guzik, <br/>
[arXiv:2009.13545 [quant-ph]](https://arxiv.org/abs/2009.13545) (2020).

[5] _One qubit as a Universal Approximant_, <br/>
A. Pérez-Salinas, D. López-Núñez, A. García-Sáez, P. Forn-Díaz, J. I. Latorre, <br/>
[arXiv:2102.04032 [quant-ph]](https://arxiv.org/abs/2102.04032) (2021).

[6] _The effect of data encoding on the expressive power of variational quantum machine learning models_, <br/>
M. Schuld, R. Sweke, J. J. Meyer, <br/>
[arXiv:2008.08605 [quant-ph]](https://arxiv.org/abs/2008.08605) (2020).
