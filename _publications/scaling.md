---
title: "Language models scale reliably with over-training and on downstream tasks"
collection: publications
permalink: /publication/dclm
excerpt: ''
date: March 2024
venue: 'ArXiv Preprint: 2403.08540'
authors: 'Samir Yitzhak Gadre, <strong>Georgios Smyrnis</strong>, Vaishaal Shankar, Suchin Gururangan, Mitchell Wortsman, Rulin Shao, Jean Mercat, Alex Fang, Jeffrey Li, Sedrick Keh, Rui Xin, Marianna Nezhurina, Igor Vasiljevic, Jenia Jitsev, Luca Soldaini, Alexandros G. Dimakis, Gabriel Ilharco, Pang Wei Koh, Shuran Song, Thomas Kollar, Yair Carmon, Achal Dave, Reinhard Heckel, Niklas Muennighoff, Ludwig Schmidt'
paperurl: https://arxiv.org/abs/2403.08540
code: https://github.com/mlfoundations/scaling
---

# Abstract

Scaling laws are useful guides for derisking expensive training runs, as they predict performance of large models using cheaper, small-scale experiments. However, there remain gaps between current scaling studies and how language models are ultimately trained and evaluated. For instance, scaling is usually studied in the compute-optimal training regime (i.e., "Chinchilla optimal" regime). In contrast, models are often over-trained to reduce inference costs. Moreover, scaling laws mostly predict loss on next-token prediction, but models are usually compared on downstream task performance. To address both shortcomings, we create a testbed of 104 models with 0.011B to 6.9B parameters trained with various numbers of tokens on three data distributions. First, we fit scaling laws that extrapolate in both the amount of over-training and the number of model parameters. This enables us to predict the validation loss of a 1.4B parameter, 900B token run (i.e., 32× over-trained) and a 6.9B parameter, 138B token run (i.e., a compute-optimal run)—each from experiments that take 300× less compute. Second, we relate the perplexity of a language model to its downstream task performance by proposing a power law. We use this law to predict top-1 error averaged over downstream tasks for the two aforementioned models, using experiments that take 20× less compute. Our experiments are available at [https://github.com/mlfoundations/scaling](https://github.com/mlfoundations/scaling).

Full paper available [here](https://arxiv.org/abs/2403.08540).
