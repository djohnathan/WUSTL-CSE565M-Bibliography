# Class Bibliography for CSE565M
This repository contains the LaTeX bibliography file for instances of 
CSE565M: Acceleration of Algorithms in Reconfigurable Logic.

## Table of Content

## Standard Operating Procedure

### Quickly adding an entry
#### Using the BibTeX citation object created by a Website
For many papers of interest, we'll access papers from IEEE, ACM, or arXiv.
These websites provide ways to access a BibTeX entry for a given paper.
##### ACM
Find the quotation marks on the DOI page for a paper of interest
![clipboard.png](inkdrop://file:a689fSe8G)
Click the quotation marks to reveal a BibTeX entry that you can either copy and paste or download

![clipboard.png](inkdrop://file:t6TqfKPEn)

### The `owner` field
When you add an entry, make sure that, in the `.bib` file, either add a
field called `owner` and use your name as the entry if it doesn't
already exist. Otherwise, append your name -- separated by a comma -- to the
name that's already there.

Example,
```
@InProceedings{randomentry2024,

  ...

  owner = {Anthony Cabrera, Roger Chamberlain},

  ...

```

##### IEEE
Find the _Cite This_ button
![clipboard.png](inkdrop://file:DfaqVohlN)
Navigate to the _BibTeX_ tab and then either copy and paste 

![clipboard.png](inkdrop://file:kzNHERLDk)

##### arXiv
Find the _Export BibTeX Citation_ link
![clipboard.png](inkdrop://file:qZZJWLjWw)

This auto-downloads the entry, which you can then copy and paste into the `.bib` file.

#### Using Google Scholar

## Current and Past Instructors


| Name | Semesters Taught |
| -------- | -------- |
| Anthony Cabrera | FL24 |
| Roger Chamberlain | SP08, FL12, SP24 |



---

## Example `.bib` entry
```
@InProceedings{Zohouri2016,
  author           = {Zohouri, Hamid Reza and Maruyama, Naoya and Smith, Aaron and Matsuda, Motohiko and Matsuoka, Satoshi},
  booktitle        = {SC '16: Proceedings of the International Conference for High Performance Computing, Networking, Storage and Analysis},
  title            = {Evaluating and Optimizing OpenCL Kernels for High Performance Computing with FPGAs},
  year             = {2016},
  month            = {Nov},
  pages            = {409-420},
  abstract         = {We evaluate the power and performance of the Rodinia benchmark suite using the Altera SDK for OpenCL targeting a Stratix V FPGA against a modern CPU and GPU. We study multiple OpenCL kernels per benchmark, ranging from direct ports of the original GPU implementations to loop-pipelined kernels specifically optimized for FPGAs. Based on our results, we find that even though OpenCL is functionally portable across devices, direct ports of GPU-optimized code do not perform well compared to kernels optimized with FPGA-specific techniques such as sliding windows. However, by exploiting FPGA-specific optimizations, it is possible to achieve up to 3.4x better power efficiency using an Altera Stratix V FPGA in comparison to an NVIDIA K20c GPU, and better run time and power efficiency in comparison to CPU. We also present preliminary results for Arria 10, which, due to hardened FPUs, exhibits noticeably better performance compared to Stratix V in floating-point-intensive benchmarks.},
  creationdate     = {2024-06-08T08:53:38},
  doi              = {10.1109/SC.2016.34},
  groups           = {cse565m},
  issn             = {2167-4337},
  keywords         = {Field programmable gate arrays;Kernel;Optimization;Benchmark testing;Programming;Graphics processing units;Performance evaluation;FPGA;Performance evaluation;OpenCL;Heterogeneous computing},
  modificationdate = {2024-06-08T08:53:38},
  owner            = {Anthony Cabrera, Roger Chamberlain},
}
```

