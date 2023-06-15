# Gene Regulatory Network Analysis

This repository contains the documentation and code for the analysis of a Gene Regulatory Network (GRN) of a Mus Musculus (common mouse). The GRN serves as an interesting case study as it allows for various analyses compatible with the human organism, enabling the prediction of genetic malformations that may lead to the development of cancers and other pathologies.

The gene regulatory network models the regulation of gene expression through the following processes:

- Genes in the DNA encode proteins.
- DNA polymerase transcribes mRNA from DNA (transcription process).
- mRNA is translated into proteins at the ribosomes (translation machinery).
- Proteins are involved in cell function.
- Transcription Factors (TFs), among other proteins, promote or inhibit the expression of specific genes (regulation).
- TFs can themselves be regulated by other proteins.
- The gene activated by the TF will be transcribed and translated into a protein.

In this network, the nodes represent genes and TFs, and the directed edges from TFs to genes or from TFs to other TFs create a regulatory relationship, leading to the activation or deactivation of a specific gene or TF. To further abstract the network, TFs can be seen as genes since TFs are simply the product of the expression of that particular gene they are named after.

## Files Structure

- **Dataset/**: Contains the dataset extracted from RegNetwork, a specialized database for gene regulatory networks. The dataset is an aggregation of information from 17 databases from different sources.
- **figs/**: This directory stores the figures and visualizations generated during the analysis.
- **Dashboard.cys**: This file represents a CytoScape dashboard, which can be used to visualize and explore the gene regulatory network.
- **GRN_Benitozzi_Squadrito.ipynb**: This Jupyter Notebook contains the code for the analysis of the gene regulatory network. It includes data preprocessing, network construction, and various analyses and visualizations.
- **Presentazione.pptx**: This PowerPoint presentation provides an overview of the project, including its goals, methodologies, and key findings.
- **Relazione.pdf**: This PDF document presents a detailed report on the analysis of the gene regulatory network, including a description of the dataset, analysis techniques, results, and conclusions.

Please refer to the individual files for more information on each component of the project.

## Getting Started

To get started with this project, follow the steps below:

1. Clone the repository to your local machine.
2. Ensure that Python and Jupyter Notebook are installed.
3. Open the `GRN_Benitozzi_Squadrito.ipynb` notebook in Jupyter Notebook.
4. Follow the instructions and run the code cells to perform the gene regulatory network analysis.
5. Refer to the generated figures and visualizations in the `figs/` directory for a better understanding of the network.
6. Explore the `Dashboard.cys` file using CytoScape to interactively visualize and analyze the gene regulatory network.
7. Review the `Presentazione.pptx` presentation and the `Relazione.pdf` report for a comprehensive overview of the project.

Enjoy exploring and analyzing the gene regulatory network!

## Contributors

- [Your Name]
- [Other contributors, if applicable]

If you have any questions or suggestions, feel free to contact us.
