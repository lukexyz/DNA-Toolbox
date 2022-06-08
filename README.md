# DNA-Toolbox
Sequence Analysis of Covid19, SARS, and MERS using BioPython

# Protein Synthesis

<p align="center">
  <img src="https://github.com/lukexyz/DNA-Toolbox/blob/master/graphics/protein_synthesis.PNG?raw=true">
</p>


<br/>  

→ :notebook_with_decorative_cover: [01-SequenceAnalysis.ipynb](notebooks/01-SequenceAnalysis.ipynb) 
> The basics of `biopython`, and the `DNA` to `RNA` to `Amino Acid` chain.

<br/>  

→ :bookmark_tabs: [02-SequenceComparison.ipynb](notebooks/02-SequenceComparison.ipynb)  
> Compare and find sequence alignments between different virus genomes (SARS, MERS, COVID-19, and Ebola)  

<br/>

→ :bookmark_tabs: [03-COVID19-GlobalAnalysis.ipynb](notebooks/03-COVID19-GlobalAnalysis.ipynb)  
> Analysis of COVID-19 sample origins and genome changes over time.

<br/>

## Installation (`WSL/Ubuntu`)

```sh
git clone https://github.com/lukexyz/DNA-Toolbox.git
conda create -n dna-toolbox python=3.6 pip jupyter
conda activate dna-toolbox
pip install -r requirements.txt
```
