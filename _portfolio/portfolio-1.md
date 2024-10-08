---
title: "Basic Reusability and Beyond: Joint Inventory and Online Assortment Optimization with Evolving Resources"
excerpt: "Author: Yukai Huang, Jacob Feldman, Heng Zhang. Submitted to Management Science"
collection: portfolio
---

**Abstract**: We study the joint inventory and online assortment optimization with reusable resources. The decision-makers decide the initial capacity of each resource before a finite selling season starts. The decision-makers offer personalized assortment in real time based on customer arrivals and remaining inventory to maximize the total expected revenue across the selling horizon. Our framework can be extended to the reusable resources. We introduce the concept of network reusability, which goes beyond the classic definition of reusable resource by allowing for the transformation of resources upon return. This advanced model captures more realistic scenarios.
The modeling richness conferred by our novel notion of reusability naturally introduces new technical hurdles when it comes to solving our joint inventory and online assortment problem. We first tackle the yet uncharted version of our problem under basic reusability, where
we can achieve the same constant factor performance guarantee for the joint optimization problem
as [Bai et al. (2022)](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4297618). Dealing with a version of the CDLP that incorporates reusability, a core piece of our result is
a novel technical argument extending that of [Bai et al. (2022)](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4297618) to establish the submodularity of the initial stocking problem. Interestingly, this overall algorithmic game plan of [Bai et al. (2022)](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4297618) is seemingly stalled when we introduce notions of network reusability into the fold: With a simple network of two nodes, we show that the CDLP can be an arbitrarily loose upper bound, which leads to simple examples demonstrating that initial inventory levels derived directly from the CDLP can be misguided. We propose a remedy called the inventory refinement
procedure that achieves a constant factor approximate performance. Our computational experiments show that our approximation framework performs well for both the product return structure and the more general network structure.
