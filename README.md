# BoostrapCC
The Boostrap Consensus Clustering method is a faster and simpler implementation of the well known resampling-based method for class discovery and visualization developed by [Monti et al](https://link.springer.com/content/pdf/10.1023/A:1023949509487.pdf). In particular, the BoostrapCC package is developed on top of the R package [ConsensusClusterPlus](https://bioconductor.org/packages/release/bioc/html/ConsensusClusterPlus.html). The BoostrapCC diminish the number of required parameters of the original idea, where both previous versions require to define the proportion of items and/or featires to sample in each iteration. In BoostrapCC, the item/featuresample is applied over a boostrap technique diminishing the number of parameters and avoiding user specific parameter selection. Another dorwback is its secuencial implementation, which make it impractical for Big Data Analytics approaches. The aim of this work is to improve ConsensusClusterPlus R library implementation in order to reduce execution time, as well as the proposal of a bootstrap sampling approach that eliminates user defined parameters.


## Authors

* **Elmer A. Fernández** - *Idea* - Centro de Investigación y Desarrollo en Inmunología y Enfermedades Infecciosas (CIDIE) - Univ. Católica de Córdoba - CONICET, Argentina 
* **Frias, Gentili** - *Implementation* - Facultad de Ingeniería - Univ. Católica de Córdoba, Argentina 
* **Saenz, M.** - *Implementation* - Facultad de Ingeniería - Univ. Católica de Córdoba, Argentina 
* **Fresno, Cristobal** - *Project development supervition* - INMEGEN - Mexico

## License

This project is licensed under the MIT License
