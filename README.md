# PetroNLP
Petro NLP is a comprehensive set of natural language processing and information extraction resources for the oil and gas industry in Portuguese. The paper "Petro NLP: Resources for natural language processing and information extraction for the oil and gas industry." describe all resources.

This repository has the NLP resources built with public information and can be openly shared. We built some of the datasets, corpora, and knowledge graphs with corporate data; they are described in the paper, but we cannot publish them.  

![alt text](https://github.com/Petroles/PetroNLP/blob/main/Graphical%20Abstract.jpg)  

The available resources are:

### Corpora

Here, you find direct links for the corpora. More information and other corpora are available on the [Petrolês website](https://petroles.puc-rio.ai/index_en.html).
- [Petrolês](https://petroles.puc-rio.ai/files/Corpora/corpus-SemProcessamento-publico-PetrolesCompleto.zip) - Consolidated file containing all Petrolês' O&G domain-specific corpora (Petrobras Technical Bulletins, Theses and Dissertations from IBICT-BDTD in petroleum-related subjects; ANP's technical reports). 
- [PetroGold](https://petroles.puc-rio.ai/files/Corpora/petrogold-v3.zip) - Gold standard treebank, with revision of the automatic annotation of lemma, POS and syntactic dependencies according to the framework of the Universal Dependencies project. The content is a subset of the Petrolês corpus. 
- [PetroNER](https://petroles.puc-rio.ai/files/Corpora/petroner-uri.zip) - Gold standard corpus annotated with named entities in the oil & gas domain. It was built from a set of 11 Technical Reports from Petrobras, which are part of the Petrolês corpus, and were preprocessed in full and morphosyntactically.
- PetroRE - The relation in PetroRE came from corporate lists; consequently, it cannot be published here.

### Knowledge Graph

- Petro KGraph Ontology
- Petro KGraph

### Embeddings Models

- [PetroVec](https://petroles.puc-rio.ai/files/embeddings/Petrovec_OeG_Word2vec.zip) - Models trained in Word2vec vectors with 100 dimensions, trained from public resources related to the O&G domain (Petrobras Technical Bulletins, Theses and Dissertations in petroleum related subjects; ANP's technical reports). More models are available on the [Petrolês website](https://petroles.puc-rio.ai/index_en.html).
- PetroOntoVec
