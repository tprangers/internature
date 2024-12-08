# INTERNATURE
## Concept
Internature est une expérience immersive qui intègre le mapping vidéo sur les parois de notre installation, accompagné par une musique ambiante et des sons immersifs. Au coeur de cet environnement, les visiteurs sont invités à intéragir avec les parois intéractives et une boule lumineuse qui déclenche un spectacle de lumière unifiant toutes les projections. Cette expérience invite les participants à reconnecter avec la nature et à redécouvrir leur lien avec elle de manière unique et émotionnelle.

## Objectif 
Ce projet explore le lien entre l'humain, la technologie et la nature, en questionnant si la technologie peut réellement remplacer la nature. L'interaction se fait en déplaçant la boule représentant notre implication en tant qu'humain sur l'environnement. En fonction de ses mouvements, les plantes poussent et prennent progressivement possession de l'espace. Lorsqu'elles occupent l'entièreté de l'espace, un spectacle lumineux qui met en valeur la beauté de la nature se déclenche. 


## Schéma d'intéractivité
```mermaid
flowchart TD
    A[Animation visuelle minime et volume en pause: état de veille] -->|Visiteur entre dans la serre| B[Déclenchement de l'audio et l'environnement intéractif]
    B --> C[Intéragir avec la sphère]
    C -->|pendant 30 secondes| D[Déclenchement de l'environnement intéractif unifié] 
    D --> |pendant 2 minutes| A[Animation visuelle minime en veille]
```

## Scénario
![scenarimage01](https://github.com/user-attachments/assets/38255ac5-1f0f-4702-a841-fe37fe86ec29)

![scenarimage02](https://github.com/user-attachments/assets/f0d83230-dba1-482f-a593-9226df00a275)

## Prototype de serre
![prototype](https://github.com/user-attachments/assets/6c94ed5d-d0e3-4c9c-a935-3e3a52411cdf)

## Prototype de la sphère
![Serre Prototype](assets/images/prototype.png)

## Schéma plantation Studio
![plantation_studio](https://github.com/user-attachments/assets/f34a8618-f61d-47c5-8583-df239a05bba7)
![plantation_projet](https://github.com/user-attachments/assets/a912db0f-90c9-41cb-aa27-22aed37be0f0)

## Schéma de connexions 
![Branchement-schéma](assets/images/branchement-refait.jpg)

## Matériel Requis
| Item                    | Stock    |
| :----------------------:| :------: |
| Ordinateur              |  1       |
| Projecteur              |  3       |
| Haut-parleur Genelec    |  2       |
| Haut-parleur Dvoom      |  10      |
| Boule semi-transparente |  1       |
| Support pour la boule   |  10      |
| Berring à bille         |  4       |
| PMW3360 Motion Sensor   |  1       |
| Module LIDAR            |  2       |
| Kinect XBOX             |  2       |
| Bandes lumineuses LED   |  2       |
| Serre portative         |  1       |

## Gestion d'équipe
### Rôles
#### Delphine (Programmeur)
- Programmation Arduino 
- Programmation TouchDesigner
- Programmation Mapping Vidéo
- Programmation Mapping Sonore
#### Kenza (Conceptrice)
- Conceptrice sonore
- Conceptrice vidéo
- Programmation Mapping
#### Khaly (AQ et Mascotte)
- S'assurer du bien-être de tous
- S'assurer de l'assurance qualité
- Aide à la programmation
- Aide conception
- Programmation Mapping Vidéo
- Programmation Mapping Sonore 
#### Sitmonternna (Scrummaster & PO)
- S'arrurer des délais et que les tâches soient fait
- Aide à la programmation
- Aide conception
- Programmation Mapping Vidéo
- Programmation Mapping Sonore

### Motivations
#### Delphine
- Utilisation de nouvelles technologies et l'apprentissage de celles-ci
- Voir le produit final
#### Kenza
- Avoir une liberté artistique
- L'objectif me parle
- Voir le produit final
#### Khaly
- L'objectif me parle
- L'ambiance visuelle est inspirante
#### Sitmonternna
- Voir le produit final
- Travailler sur un gros projet multimédia

### Échéancier 
![Échéancier](assets/images/echeancier.png)

## Sources
### Recherche Technique
- [Faire des tests de mouvement - Berrings](https://youtu.be/VbxcjOQlUPA?si=PVR5ewIHE-6zU1Ci&t=27)
- [Utiliser PMW3360 Motion Sensor](https://www.youtube.com/watch?v=CSA7Ih7nAls)
- [Vidéo mapping dans touch designer](https://www.youtube.com/watch?v=mTH7ZB4x47Q)

### Matériel
- [Serre](https://www.amazon.ca/portable-galvanis%C3%A9-sup%C3%A9rieures-diagonaux-enroulables/dp/B0D8KQLJKN/ref=sr_1_3_sspa?crid=2TCDEG8L2V37W&dib=eyJ2IjoiMSJ9.B9dkS9qJ4UP0glIJoNKfQfubm9D9_JpV4kwmr-b9QMy_pFipM3myhuM8AGfqy0UCzOLmRVjzzKrIt6XvA_FCsEVtyxqiWqjRNqZdfcVFX1NGWZkyTCtgESnQjziIa5mWrQCDEeCcg1GblIrf32Z8QpQxs0hifJ8Jx19wUkwSnMlPh8LfF3fSiQl9htVVMUOhGmjbnTmvfn9qJgUujgEZBlOYyN4ZC5I1i2Ur0qT8kC7ZIeOL6UrO_rjYAe__2r-WXkgGeM1Sx5p48_hQJ8Pafxawq2VdRhveNh1WOB4kT-Q.h8swQdtDTEyr1g5o8Cz7PfF4CAVuGXehVrnHWS3JJ-s&dib_tag=se&keywords=walk%2Bin%2Btunnel%2Bgreenhouse&qid=1731963509&sprefix=walk%2Bin%2Btunnel%2Bgre%2Caps%2C62&sr=8-3-spons&sp_csd=d2lkZ2V0TmFtZT1zcF9hdGY&th=1)
- [Berrings à bille](Statics.teams.cdn.office.net/evergreen-assets/safelinks/1/atp-safelinks.html)
- [PMW3360 Motion Sensor](https://lectronz.com/products/pmw3360-motion-sensor)

### Recherches d'inspirations artistiques
#### Visuel
- [teamLab Borderless Hamburg: Digital Art Museum](https://www.youtube.com/watch?v=rwnFygwoqOQ)
- [Human Nature- an interactive audiovisual installation in the Satosphere](https://www.youtube.com/watch?v=Kt4FWBp3Xoo&t=66s)
- [Hopscotch Portland - An Immersive Art Experience](https://www.youtube.com/watch?v=MB3wyhu2pOw&t=4s)
- [Beautiful immersive experience by artists Adrien M & Claire B](https://www.youtube.com/watch?v=fb5QgYMOgOo)

#### Sonore
- [Composition sonore venant de *The Day We Left Field* de TUNDRA](https://m.youtube.com/watch?v=4XeSs9a1rLQ&list=PLBBz6wzKh2tMFQ-kCNZKN96oCJCIcehtk&index=1&pp=gAQBiAQB)
- [*Infinity flow* de ELEVENPLAY × Rhizomatiks](https://www.youtube.com/watch?app=desktop&v=xTaIXO6ufGw)
- [Composition de la vidéo *Planets* de Teamlab](https://www.youtube.com/watch?app=desktop&v=-uJTk_mRmUY)
- [*piano077* de Oscar Scannell](https://www.youtube.com/watch?app=desktop&v=oGSitxblbAg)
- [Composition sonore venant de *Lost & Found* de Max Lemmit](https://www.youtube.com/watch?app=desktop&v=gpSLtYSHFmg)
