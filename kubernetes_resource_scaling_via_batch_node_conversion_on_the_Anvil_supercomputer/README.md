# Kubernetes Resource Scaling via Batch Node Conversion on the Anvil Supercomputer

[DOI]

**Authors**
* Erik Gough, Purdue University
* LJ Lumas, Purdue University


**Abstract:**
We will explore our approach to reallocating compute nodes in an HPC system managed by Slurm, converting them from "batch" nodes to "cloud" nodes within a Kubernetes resource. We developed and implemented these methods on the Anvil ACCESS resource to support large-scale educational and training workshops. By temporarily shifting batch nodes to cloud nodes, we overcame capacity limitations on Anvil's Kubernetes infrastructure, enabling one workshop to scale up to 75 computing sessions, a 3.5x increase over what was possible with their allocation. We will give an overview of Anvil's xCAT + masterless puppet configuration management stack and introduce a script that facilitates the conversion of HPC batch nodes to Anvil Kubernetes nodes and back, providing flexible resource management through command-line options. While each institution's software stack is unique, our experience and guidelines offer a foundation that others can adapt to achieve similar success in their own environments.
