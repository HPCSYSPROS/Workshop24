# Beyond the Hype: Uncovering the Real I/O Needs of LLMs

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.15724856.svg)](https://doi.org/10.5281/zenodo.15724856)

**Authors**
* Subramanian Kartik, VAST Data Inc
* Glenn K. Lockwood, Microsoft Corporation

**Abstract:**
In this talk, we will address misconceptions about the I/O requirements for training large language models (LLMs) at scale. Contrary to popular belief, the read workload is not the biggest I/O challenge in training and does not intrinsically require extreme IOPS nor bandwidth. Rather, the write workload, driven by checkpointing, imposes the highest demands on storage. Despite this, the write bandwidth for even the largest frontier LLMs is also modest even at massive scale, and we will demonstrate this quantitatively through a simple performance model. We will also explore strategies to optimize write performance of training frameworks, further reducing the need for boutique storage systems optimized for write throughput. This presentation aims to provide a clear, realistic view of the I/O patterns in LLM training based on our real-world experience, dispelling myths that may otherwise result in overspecifying and overspending on storage for AI workloads.
