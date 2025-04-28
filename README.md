# Toward Generating Experiment-Specific Notebooks in FABRIC

[![JupyterBook](https://github.com/UCAR-SEA/SEA-ISS-2025-Toward-Generating-Experiment-Specific-Notebooks-in-Fabric/actions/workflows/deploy.yml/badge.svg)](https://github.com/UCAR-SEA/SEA-ISS-2025-Toward-Generating-Experiment-Specific-Notebooks-in-Fabric/actions/workflows/deploy.yml)
[![Made withJupyter](https://img.shields.io/badge/Made%20with-Jupyter-green?style=flat-square&logo=Jupyter&color=green)](https://jupyter.org/try)
![Static Badge](https://img.shields.io/badge/DOI-10.XXXXX%2Fnnnnn-blue)

**Authors**: Mami Hayashida, Joshna Kurra, Zongming Fei, James Griffioen

**Abstract**:
Jupyter notebooks are now widely used by the research community to set up, launch, run, analyze, and document scientific experiments. The massive number of example notebooks available not only has made it easier for researchers to write notebooks, but also represents a wealth of data that can be used by Generative AI systems to automatically generate experiment-specific notebooks.

This paper describes the use of RAG-based AI techniques to automatically generate jupyter notebooks in the context of FABRIC, an NSF-funded next generation network testbed that consists of over 30 sites. To program the FABRIC testbed, including reserving and managing resources across the network, researchers must use FABlib, a python API. While an extensive collection of example notebooks that use FABlib are available to users as well as detailed documentation regarding the FABlib API, finding the information needed to create a new FABRIC notebook can be difficult, especially for first-time users. Moreover, using popular GenAI tools to assist with FABRIC code generation often yields poor results as even large general-usage LLMs lack testbed-specific knowledge.

To address this gap, we have implemented an AI-based tool that leverages the power of LLMs and Retrieval Augmented Generation(RAG) to generate FABRIC-specific code based on the user's spefication. Our initial test results show that RAG-enhanced LLMs can significantly improve the accuracy of the generated code for FABRIC experiments.

**Keywords:** Retrieval-Augmented Generation, Jupyter Notebooks, Python Code Generation, NL2Code, Large Language Models, Low-Cost models

**Acknowledgements**: Special thanks to Komal Thareja for helping us with the test result evaluation and Vikram Gazula for setting up the server and providing the hardware details. This research was supported by the National Science Foundation Awards 1935966 and 2330891 and 2029235.

---
