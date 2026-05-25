---
title: Écoacoustique et paysages sonores  
weight: 6
---

## Qu'est-ce que l'écoacoustique ?  

**Définition** :  
L'écoacoustique est une discipline qui utilise les sons de l'environnement (le paysage_sonore) pour étudier la biodiversité et les écosystèmes. 
L'écoacoustique se distingue de la bioacoustique car elle considère le son dans un contexte de processus écologiques plutôt que comme simple signal de communication.  

Les indices acoustiques sont les principaux outils utilisés en écoacoustique.

> [!Info] Source
> Sueur, J. & Farina, A. (2015). Ecoacoustics: the Ecological Investigation and Interpretation of Environmental Sound. Biosemiotics, 8, 493–502.


## Articles fondateurs en écoacoustique  

Le terme d'écoacoustique n'apparaît qu'en 2015, mais le concept était déjà présent depuis la fin des années 2000.  
Voici quelques articles qui ont marqué l'évolution de la discipline :  
1. Sueur J, Pavoine S, Hamerlynck O, Duvail, S. 2008. Rapid acoustic survey for biodiversity appraisal. PLOS ONE 3 (art. e4065).
--> Premier indice acoustique : Acoustic Entropy Index, créé sur le même principe que l'indice de Shannon  

![Sueur et al. 2008](/pam-workshop/fr/workshop/analyses/ecoacoustics/Sueur2008.png) 


2. Pijanowski BC, Villanueva-Rivera LJ, Dumyahn SL, Farina A, Krause BL, Napoletano BM, Gage SH, Pieretti N. 2011. Soundscape ecology: The science of sound in the landscape. BioScience 61: 203–216.
--> définition du concept de soundscape ecology, sur le modèle de landscape ecology avec les notions de biophonie, anthropophonie et géophonie   

![Pijanowski et al. 2011](/pam-workshop/fr/workshop/analyses/ecoacoustics/pijanowski2011.png) 

3. Sueur J, Farina A. 2015. Ecoacoustics: The ecological investigation and interpretation of environmental sound. Biosemiotics 8: 493–502.
--> Apparition du terme d'écoacoustique

![Sueur et Farina 2015](/pam-workshop/fr/workshop/analyses/ecoacoustics/SueurFarina2015.png) 

## Les indices acoustiques  

### Qu'est-ce qu'un indice acoustique ?

Un indice acoustique quantifie la distribution et la structure de l'énergie acoustique dans un enregistrement sonore. Il permet ainsi de caractériser les caractéristiques spectrales et temporelles d'un paysage sonore.
Cette quantification de la diversité ou complexité acoustique est utilisée comme une estimation de la diversité ou complexité biologique présente dans l'écosystème.  

### Applications  

Les indices acoustiques peuvent être mis en relation avec la biodiversité, les caractéristiques du paysage et changements anthropiques.  


> [!example] Exemples d'applications
> - Caractérisation de l'intégrité d'un habitat forestier ([[references|Sueur et al. 2008]])
> - Estimation de la richesse spécifique sur des sites forestiers ([[references|Depraetere et al. 2012]])
> - Suivi de tendances spatio-temporelles de la biophonie, géophonie ou anthropophonie ([[references|Halfwerk et al. 2011; Tucker et al. 2014; Erbe et al. 2015; Fuller et al. 2015]])
> - Étude de la phénologie de communautés ([[references|Farina et al. 2011; Desjonquères et al. 2015; Nedelec et al. 2015; Bittencourt et al. 2016]])



### Quels indices acoustiques existent ?

Plus de 60 indices acoustiques ont été développés ces 15 dernières années (Buxton et al., 2018), mais certains sont plus couramment utilisés que d'autres. 
Les indices acoustiques les plus utilisés sont: 
- Acoustic Complexity Index (ACI)
- Acoustic Diversity Index (ADI)
- Acoustic Evenness Index (AEI)
- Bioacoustic Index (BIO)
- Total Entropy (H)
- Normalized Difference Soundscape Index (NDSI)


| Indice                                          | Description                                                                                                                                                 | Valeurs                                                      | Interprétation                                                                                                                                                                                                                                                                                          | Référence                       |
| ----------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------- |
| *Acoustic Complexity Index (ACI)*               | Quantifie la variabilité des intensités sonores, en minimisant l’influence des bruits anthropiques                                                          | [0, +∞]                                                      | **Valeurs élevées** : forte variabilité (e.g. chants d’oiseaux, stridulation d’insectes, ou anthropophonie) <br><br>**Valeurs faibles**: sons constants (e.g. chants de cigale)                                                                                                                         | Pieretti et al. (2011)          |
| *Acoustic diversity index (ADI)*                | Mesure la distribution de l’énergie sonore dans les bandes de fréquence du spectrogramme                                                                    | [0, log(N)]<br><br>N = nombre de fréquences de bande de 10Hz | **Valeurs élevées** : sons répartis dans l’ensemble des bandes de fréquence (i.e. diversité des fréquences)<br><br>**Valeurs faibles** : son concentré dans une bande de fréquence.<br><br>Selon l’Acoustic Niche Hypothesis, des valeurs élevées devraient donc traduire un nombre important d’espèces | Villanueva-Rivera et al. (2011) |
| *Acoustic Evenness Index (AEI)*                 | Divise le spectrogramme en bandes de fréquence et utilise le coefficient de Gini (Gini, 1921) pour mesurer l’uniformité du son dans ces bandes de fréquence | [0, 1]                                                       | Inverse de l’ADI.<br><br>Une forte biodiversité devrait être associée à de faibles valeurs d’AEI                                                                                                                                                                                                        | Villanueva-Rivera et al. (2011) |
| *Bioacoustic Index (BIO)*                       | Produit de l’amplitude et du nombre de bandes de fréquences occupées                                                                                        | [0, +∞]                                                      | **Valeurs élevées** : forte disparité entre l’amplitude des bandes de fréquence. <br><br>Indice fortement associé à la richesse spécifique aviaire (Eldridge et al. 2018, Bradfer-Lawrence et al. 2020)                                                                                                 | Boelman et al.(2007)            |
| *Total Entropy (H)*                             | Basé sur l’indice de Shannon, estime la dispersion de l’énergie à partir des caractéristiques temporelles et spectrales                                     | [0, 1]                                                       | **Valeurs proches de 1** : bonne répartition des fréquences émises (i.e. grande diversité de signaux, forte richesse spécifique)                                                                                                                                                                        | Sueur et al. (2008)             |
| *Normalized Difference Soundscape Index (NDSI)* | Ratio entre sons d’origine anthropique (fréquence de 1-2 kHz) et d’origine biologique (fréquence entre 2 et 8 kHz)                                          | [-1, 1]                                                      | **Valeurs proches de -1** : paysage sonore dominé par l’anthropophonie<br><br>**Valeurs proches de +1** : paysage sonore dominé par la biophonie<br><br>Corrélé à la diversité des sons biotiques et abiotiques                                                                                         | Kasten et al. (2012             |



### Comment calculer un indice acoustique ?

Plusieurs librairies R et Python ont été développées pour calculer des indices acoustiques à partir d'enregistrements.
Les plus utilisées sont [Seewave](https://cran.r-project.org/web/packages/seewave/index.html) et [Soundecology](https://cran.r-project.org/web/packages/soundecology/index.html) sur R, [Scikit-Maad](https://scikit-maad.github.io/) sur Python.


### Comment les interpréter ? 

> [!info] Pour en savoir plus
> 
> L'[Acoustic Index User's Guide](https://ecohack.shinyapps.io/Acoustic_Index_Users_Guide/) détaille comment chaque indice est calculé avec différents exemples d'enregistrements.
> C'est un bon guide tant pour choisir l'indice acoustique à utiliser que pour interpréter les résultats.

 

