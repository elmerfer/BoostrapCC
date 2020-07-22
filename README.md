# BootstrapCC
The Bootstrap Consensus Clustering method is a faster and simpler implementation of the well known resampling-based method for class discovery and visualization developed by [Monti et al](https://link.springer.com/content/pdf/10.1023/A:1023949509487.pdf). In particular, the BootstrapCC package was developed on top of the R package [ConsensusClusterPlus](https://bioconductor.org/packages/release/bioc/html/ConsensusClusterPlus.html). The BootstrapCC diminish the number of required parameters on the original implementation, that requires to define the proportion of items and/or features to sample in each iteration. In BootstrapCC, the item/feature sample is applied over a bootstrap technique diminishing the number of parameters and avoiding user specific parameter selection. Another drawback is its secuencial implementation, which make it impractical for Big Data Analytics approaches. The aim of this work is to improve the R library implementation, ConsensusClusterPlus, in order to reduce execution time  by paralelizing critical secuencial steps, as well as the proposal of a bootstrap sampling approach that eliminates user defined parameters.

# NOTE:

We have also developed a new version in python [BootstrapCCpy](https://github.com/NNelo/BootstrapCCpy)

## Installation
```
install.packages("devtools")
library(devtools)
install_github("elmerfer/BootstrapCC")
```
## Authors

* **Elmer A. Fernández** - *Idea* - Centro de Investigación y Desarrollo en Inmunología y Enfermedades Infecciosas (CIDIE) - Univ. Católica de Córdoba - CONICET, Argentina 
* **Frias, Gentili** - *Implementation* - Facultad de Ingeniería - Univ. Católica de Córdoba, Argentina 
* **Saenz, M.** - *Implementation* - Facultad de Ingeniería - Univ. Católica de Córdoba, Argentina 
* **Fresno, Cristobal** - *Project development supervision* - INMEGEN - Mexico

## License

This project is licensed under the MIT License
