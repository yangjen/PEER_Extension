# PEER_Extension
Revisiting Sparse Expert Models: Extensions of the Mixture of Million Experts

Code for AI602 Advance Deep Learning Final Project

We conduct a focused reimplementation and evaluation of the Product-Key Expert Routing (PEER) method proposed in Mixture of Million Experts under strict FLOPs constraints. Our study revisits the effectiveness of sparse expert routing in language modeling tasks by comparing a dense transformer baseline, the original PEER design, and an improved PEER variant incorporating dynamic top-k routing and expert normalization. All models are trained under an equivalent compute budget of 6E+10 FLOPs. While the dense baseline exhibits overfitting, our PEER implementation achieves a validation perplexity of 158, and the improved PEER reduces this further to 84.3. These results highlight that, even in low-resource regimes, sparse expert models can offer superior generalization and efficiency over dense counterparts, reinforcing the scalability potential outlined in the original PEER formulation.
