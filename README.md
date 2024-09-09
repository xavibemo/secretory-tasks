# Curation of Secretory Tasks

A repository dedicated to curate and incorporate genome-scale reconstructions of secretory pathways from [Gutierrez _et al._ 2020](https://doi.org/10.1038/s41467-019-13867-y) as Secretory Tasks described by [Masson _et al._ 2024](https://doi.org/10.1016/j.ymben.2023.12.006.). Secretory Tasks were incorporated to the latest version of the Human-GEM metabolic model ([Robinson _et al._ 2020](https://doi.org/10.1126/scisignal.aaz1482)).

```bash
project
|
|- README
|
|- data/
|- code/
|- results/
|  |- Human-GEM-secretory.xml[.gz]          # Updated metabolic model
|  |- task-metadata-secretory.txt           # Secretory task metadata
|  |- task-structure-secretory[.json|.pkl]  # Task to Reaction to Gene relationships
```

## References

Gutierrez, J.M., Feizi, A., Li, S. _et al._ Genome-scale reconstructions of the mammalian secretory pathway predict metabolic costs and limitations of protein secretion. _Nat Commun_ 11, 68 (2020). https://doi.org/10.1038/s41467-019-13867-y

Helen 0. Masson _et al._ Inferring secretory and metabolic pathway activity from omic data with secCellFie. _Metabolic Engineering_. 24, 2024. https://doi.org/10.1016/j.ymben.2023.12.006.

Jonathan L. Robinson _et al._ An atlas of human metabolism. _Sci. Signal._ 13, eaaz1482(2020). https://doi.org/10.1126/scisignal.aaz1482