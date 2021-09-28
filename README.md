# OC-DS-P6-Classifiez_automatiquement_biens_consommation
Formation OpenClassrooms - Parcours data scientist - Projet n°6 - Classifiez automatiquement des biens de consommation

## Classification automatique d’objets de biens de consommation 

L’entreprise __"Place de marché”__, qui souhaite lancer une marketplace e-commerce.
Sur la place de marché, des vendeurs proposent des articles à des acheteurs en postant une photo et une description.

Pour l'instant, l'attribution de la catégorie d'un article est effectuée manuellement par les vendeurs et est donc peu fiable. De plus, le volume des articles est pour l’instant très petit.

Pour rendre l’expérience utilisateur des vendeurs (faciliter la mise en ligne de nouveaux articles) et des acheteurs (faciliter la recherche de produits) la plus fluide possible et dans l'optique d'un passage à l'échelle, il devient nécessaire d'automatiser cette tâche.

## Les données
Jeu de données d’articles avec le [lien](https://s3-eu-west-1.amazonaws.com/static.oc-static.com/prod/courses/files/Parcours_data_scientist/Projet+-+Textimage+DAS+V2/Dataset+projet+pre%CC%81traitement+textes+images.zip) pour télécharger la photo et une description associée.

## Mission
- réaliser une première étude de faisabilité d'un moteur de classification d'articles basé sur une image et une description pour l'automatisation de l'attribution de la catégorie de l'article.

- analyser le jeu de données en réalisant un prétraitement des images et des descriptions des produits, une réduction de dimension, puis un clustering. 
Les résultats du clustering seront présentés sous la forme d’une représentation en deux dimensions à déterminer, qui ’illustrera le fait que les caractéristiques extraites permettent de regrouper des produits de même catégorie.

![P6_Processus](https://user-images.githubusercontent.com/71518818/135125486-52fa5e54-5ad3-4172-aba7-c9ddb1193ba6.png)

## Contraintes
- Afin d’extraire les features, mettre en œuvre a minima un algorithme de type SIFT / ORB / SURF.
- Un algorithme de type CNN Transfer Learning peut éventuellement être utilisé en complément, s’il peut apporter un éclairage supplémentaire à la démonstration.

**NLP**
******

**MÉTHODES CLASSIQUES**
*****
![P6_NLP_1](https://user-images.githubusercontent.com/71518818/135125773-7b220ba1-ca2d-47e5-99fc-d1a874c1c93f.png)
![P6_NLP_2](https://user-images.githubusercontent.com/71518818/135125994-4e89e96a-c552-4a19-ad0b-eae2745f28d3.png)
![P6_NLP_3](https://user-images.githubusercontent.com/71518818/135126086-4de28394-c39a-497c-82c3-876f4d48653a.png)
![P6_NLP_4](https://user-images.githubusercontent.com/71518818/135126262-cc08bef4-5c02-4cf0-94a6-165ffd53e8be.png)
![P6_NLP_5](https://user-images.githubusercontent.com/71518818/135126152-e9c315d1-8975-4652-a028-1003b930fc62.png)

**RÉSEAUX DE NEURONES - TRANSFERT LEARNING**
*****
![P6_NLP_6](https://user-images.githubusercontent.com/71518818/135127835-54eec882-bdad-404e-8840-500355be1f1f.png)
![P6_NLP_7](https://user-images.githubusercontent.com/71518818/135127894-d2c62948-56d5-4210-8ad8-d1e81a58a24a.png)
![P6_NLP_8](https://user-images.githubusercontent.com/71518818/135127925-bc2f33ed-7b4c-4dba-b5ac-7867fb66bb96.png)


**IMAGES**
******
![P6_IMG_1](https://user-images.githubusercontent.com/71518818/135126328-3bd5080a-fb5f-42b8-8d6d-9cbed57f7b7b.png)
![P6_IMG_2](https://user-images.githubusercontent.com/71518818/135126428-05e3046c-1e80-4714-b827-6d0e25319a21.png)
![P6_IMG_3](https://user-images.githubusercontent.com/71518818/135126463-6c4842fc-250e-4af3-9247-8cb39db11311.png)
![P6_IMG_4](https://user-images.githubusercontent.com/71518818/135126503-01a489ea-e2ec-4cd8-977a-a52769bce7f7.png)
![P6_IMG_5](https://user-images.githubusercontent.com/71518818/135126545-00303f1a-ccd3-4e32-8919-37a1ab932539.png)

**COMBINAISON TEXTE &IMAGES**
******
![P6_COMBI](https://user-images.githubusercontent.com/71518818/135126632-7ede28fb-21be-4693-ad57-12f816e64015.png)
