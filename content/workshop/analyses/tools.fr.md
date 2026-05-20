---
title: Les outils
weight: 4
---

## Les approches

### Réseaux de neurones

Les volumes de données produits par un suivi acoustique passif peuvent être très conséquents, notamment sur des suivis à long terme. L'analyse manuelle de la totalité de ces enregistrements est souvent impossible. 

Le développement de l'intelligence artificielle et notamment des réseaux de neurones profonds a permis la conception d'outils informatiques utiles pour le traitement des gros volumes de données. Il existe désormais des outils tels que BirdNET et YOLO dont les interfaces ne demandent pas de trop grandes compétences en informatique.


### Indices acoustiques

#### Qu'est-ce qu'un indice acoustique ?

Un indice acoustique quantifie la distribution et la structure de l'énergie acoustique dans un enregistrement sonore.
Il permet ainsi de caractériser les caractéristiques spectrales et temporelles d'un paysage sonore.
Cette quantification de la diversité ou complexité acoustique est utilisée comme une estimation de la diversité ou complexité biologique présente dans l'écosystème. 

Les indices acoustiques sont les principaux outils utilisés en écoacoustique. 


> [!TIP] Exemples d'applications
> - Caractérisation de l'intégrité d'un habitat forestier (Sueur et al. 2008)
> - Estimation de la richesse spécifique sur des sites forestiers (Depraetere et al. 2012)
> - Suivi de tendances spatio-temporelles de la biophonie, géophonie ou anthropophonie (Halfwerk et al. 2011; Tucker et al. 2014; Erbe et al. 2015; Fuller et al. 2015)
> - Étude de la phénologie de communautés (Farina et al. 2011; Desjonquères et al. 2015; Nedelec et al. 2015; Bittencourt et al. 2016)


#### Quels indices acoustiques utiliser ?

Plus de 60 indices acoustiques ont été développés ces 15 dernières années (Buxton et al., 2018), mais certains sont plus couramment utilisés que d'autres. 
Les indices acoustiques les plus utilisés sont: 
- Acoustic Complexity Index (ACI)
- Acoustic Diversity Index (ADI)
- Acoustic Evenness Index (AEI)
- Bioacoustic Index (BIO)
- Total Entropy (H)
- Normalized Difference Soundscape Index (NDSI)


#### Comment calculer un indice acoustique ?

Plusieurs librairies R et Python ont été développées pour calculer des indices acoustiques à partir d'enregistrements.
Les plus utilisées sont [Seewave](https://cran.r-project.org/web/packages/seewave/index.html) et [Soundecology](https://cran.r-project.org/web/packages/soundecology/index.html) sur R, [Scikit-Maad](https://scikit-maad.github.io/) sur Python.



> [!TIP] Pour en savoir plus
> 
> L'[Acoustic Index User's Guide](https://ecohack.shinyapps.io/Acoustic_Index_Users_Guide/) détaille comment chaque indice est calculé avec différents exemples d'enregistrements.
> C'est un bon guide tant pour choisir l'indice acoustique à utiliser que pour interpréter les résultats.



## Logiciels

Plusieurs logiciels offrent des outils de visualisation et d'analyse d'enregistrements sonores. 
Certains logiciels open-source gratuits comme [Audacity](https://manual.audacityteam.org/index.html) offrent des fonctionnalités de base pour visualiser l'enregistrement avant d'effectuer une analyse plus poussée sous R ou Python.

D'autres logiciels payants comme Raven ou AviSoft ont des outils d'analyse intégrés.

### Packages R

*[Seewave](https://cran.r-project.org/web/packages/seewave/index.html)* : Package R, fournissant une gamme d'outils pour l'analyse bioacoustique, notamment la visualisation, l'annotation et le calcul d'indices acoustiques.

*[Soundecology](https://cran.r-project.org/web/packages/soundecology/index.html)* : Package R, fournissant des fonctions pour calculer des indices acoustiques à partir de spectrogrammes.  

*[WarbleR](https://cran.r-project.org/web/packages/warbleR/index.html)* : Package R, fournissant des fonctions pour le traitement par lots de signaux bioacoustiques, y compris la visualisation de spectrogrammes, l'extraction de caractéristiques acoustiques et l'évaluation de la qualité d'enregistrement.  

- [tuneR](https://cran.r-project.org/web/packages/tuneR/index.html)    
- [bioacoustics](https://cran.r-project.org/web/packages/bioacoustics/index.html)


### Librairies Python

- librosa
- opensoundscape    
- [scikit-maad](https://scikit-maad.github.io/)
