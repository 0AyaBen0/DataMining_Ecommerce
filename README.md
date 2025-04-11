1. Contexte du Projet
Avec l'essor du commerce en ligne, les entreprises cherchent de plus en plus à comprendre le comportement
des utilisateurs sur leurs sites e-commerce. L'analyse des données peut fournir des insights précieux sur les
préférences des clients, les tendances des ventes, et les performances des produits, permettant ainsi d'optimiser
les stratégies marketing et d'améliorer l'expérience utilisateur.

ce projet est realise par:
Abaloun Meriem
Bendahmane Aya

Vous trouverez dans ce dossier les fichiers utilisés pour le projet d'étude du site e-commerce www.jumia.ma

1. Nous avons commencé par effectuer du web scraping sur le site. Ce travail est contenu dans le fichier web_scraping.ipynb
2. Ensuite, nous avons généré un dataset de faux utilisateurs en utilisant la librairie Faker, 
car les informations des vrais utilisateurs sont confidentielles et nous n'avons pas accès à ce type de données
Ce processus est documenté dans le fichier fake_users.ipynb
3. Par la suite, nous avons appliqué des modèles d'apprentissage automatique sur les deux datasets :
	- Produits_ML.ipynb pour les produits,
	- Users_ML.ipynb pour les utilisateurs.
4. Nous avons également manipulé les dataset de faux utilisateurs et produits avec Orange Data Mining
ce qui est enregistré dans le fichier users.ows et produit.ows
5. Enfin, nous avons rassemblé les deux datasets dans un fichier tableau afin de créer les dashboards. 
Ce travail est disponible dans le fichier projet_tableau.twb
