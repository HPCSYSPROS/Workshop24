# Increasing Effective Storage Capacity with Hierarchical Storage Management (HSM) for NCAR’s Campaign Storage

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.16541348.svg)](https://doi.org/10.5281/zenodo.16541348)

**Authors**
* Aric Werner, National Center for Atmospheric Research (NCAR)
* Joseph Mendoza, National Center for Atmospheric Research (NCAR)
* Ben Kirk, National Center for Atmospheric Research (NCAR)

**Abstract:**
With the cost of tape-based storage being a fraction of the price of disk-based storage, using tape is an appealing way to drive costs downward, but this is not without challenges. NCAR’s Campaign Storage (CS) is a 120 PB disk-based IBM Storage Scale system that is projected to be outgrown by storage demands, but it has enough cold data that there is potential to offload to tape when data retrieval time requirements permit doing so. One notable challenge is reconciling users’ desire for a single namespace with the need to prevent issues that can occur when users have unfettered ability to read files. In this submission we introduce an architecture for solving issues including (1) a utility that enables users to self-request file migrations/recalls, (2) Storage Scale policies that can be used to handle migration/recall requests in a constrained way, and (3) a cost incentive for encouraging use of tape.
