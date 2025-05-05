# ISGDA Overview
- We created an inductive, supervised method of rare disease diagnosis using knowledge-enhanced learning.
- This method is inherently inductive as it is based on the phenotype ontology (Upheno).
- A supervised signal (in Graph 4) is applied, to ensure that the performance is best. This signal tells the model what it needs to learn, rather than leaving it to guess what is important.
- It is a ranking approach that produces scores for gene-disease associations. Therefore, for our query 'D', 'G' is ranked.

# Main ontology used (for cross-species phenotypic mapping)

Upheno (https://github.com/obophenotype/upheno.git)

# Dependencies
- The code uses the mOWL library (https://github.com/bio-ontology-research-group/mowl)
- JAVA and JDK required
- Python==3.10.16
- mOWL==1.0.1
- PyKEEN==1.11.0
- Class Resolver==0.5.4
- Scipy==1.13.1
- Numpy==1.26.4
  
  
# Content
This repository includes the data (general.zip, graph structures.zip, and embeddings.zip) and source code (in src.zip) to produce scores using:
- Direct GDA ranking
- BMA-based GDA ranking

