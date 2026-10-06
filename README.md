# Supplementary material for [KK26]

**Authors of [KK26]:** [Samuel Kittle](https://github.com/samuel-kittle) and [Constantin Kogler](https://github.com/ckkogler).

This repository contains supplementary material for the paper **[KK26]**: five research manuscripts and one accompanying research conversation transcript. The paper is not yet available on arXiv; **[KK26]** is used here as an informal reference, pending public bibliographic details.

The collection records model-generated arguments that contributed to the development of [KK26], together with subsequent explorations based on that paper. The manuscripts identify GPT-6 Astra as their author and describe prompting by C.K. using the prompter's local context. The five research manuscripts were revised on 5 October 2026 to correct and complete references and attributions; the higher-dimensional manuscript also now explains the equivalence between sublinear linear-part entropy and virtual solvability. The conversation transcript is preserved as supplied. Earlier manuscript versions remain available in the Git history.

## Research manuscripts

| File | Description | Relation to [KK26] |
| --- | --- | --- |
| [hochman-dimension.pdf](hochman-dimension.pdf) | *Gaussian Smoothing and the Dimension of Self-Similar Measures on the Line*. A proposed Gaussian-channel approach to dimension and superexponential concentration for self-similar measures on the real line. | Model output that led to [KK26]. |
| [transcendental-bernoulli-convolutions.pdf](transcendental-bernoulli-convolutions.pdf) | *Gaussian Channels and Transcendental Bernoulli Convolutions*. A proposed Gaussian-channel proof of the full-dimension theorem for transcendental Bernoulli convolutions. | Model output that led to [KK26]. |
| [generalized-exact-overlaps.pdf](generalized-exact-overlaps.pdf) | *The Generalized Exact Overlaps Conjecture on the Dimension of Self-Similar Measures on the Line*. A candidate proof using Poisson partitions, entropy loss, and local variance. | Model output that led to [KK26]. |
| [sharp-entropy-loss.pdf](sharp-entropy-loss.pdf) | *A Sharp Logarithmic Bound for Entropy Loss under Addition*. An exploration of logarithmic dependence on the number of summands and a refinement in terms of their individual variance energies. | Model output based on [KK26]. |
| [virtually-solvable-overlaps.pdf](virtually-solvable-overlaps.pdf) | *The Dimension Formula for Self-Similar Measures with Virtually Solvable Rotations*. An exploration of higher-dimensional extensions involving invariant quotients and conditional measures. | Model output based on [KK26]. |

## Citation revision (5 October 2026)

The higher-dimensional manuscript now cites Breuillard's strong Tits alternative, Tits' classical theorem, and Kesten's amenability criterion, with an argument that also covers nonsymmetric rotation laws. It credits Falconer and Jin for the dimension-conservation input cited through Hochman. Across the collection, the review restored missing author names, clarified the origin of variance summation and standard information inequalities, and completed bibliographic details. The established arithmetic attributions to Breuillard–Varjú, Mahler, and Dimitrov (through Rapaport–Varjú) were retained and checked.

## Research conversation transcript

| File | Coverage |
| --- | --- |
| [chat_log_dimension_papers.pdf](chat_log_dimension_papers.pdf) | Research conversations from 27 September to 5 October 2026 concerning the dimension theorem, transcendental Bernoulli convolutions, and generalized exact overlaps; accompanies the first three manuscripts above. |

The transcript preserves prompts, responses, and progress updates within the scope described in the PDF. It is a conversation record rather than a complete execution log; referenced attachments and local context are not necessarily included in this repository.

## Status and use

These files document the research process and are supplementary to [KK26]. The manuscripts originated as model outputs. Their red provenance notices retain the original wording; the citation revisions are documented in this README. Several explicitly identify their arguments as proposed proofs or proof candidates. The citation review is not a certification of all proposed proofs. Their inclusion here does not establish the correctness of every claim or identify every statement with a result of [KK26]. Consult [KK26] for the paper's final statements and proofs when it becomes available.

For the present, refer to the main paper informally as **[KK26] (2026)** and identify any supplementary manuscript or transcript by its title and filename. A public citation and arXiv link can be added when available.
