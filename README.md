# Attendus pour le projet Python pour la Data Science

Ce projet Git a pour but d'illustrer les attendus du projet pour le cours Python pour la Data Science à l'ENSAE.

Il reproduit un repo git satisfaisant pour la reproductibilité.


## Structure du projet

Ne pas hésiter à installer `tree` dans le terminal pour faciliter la visualisation :

```{bash}
sudo apt update
sudo apt install tree
tree
```

On obtient alors un résultat de ce genre :

```{bash}
attendus_pythonds_ensae
├── images
│   └── iris_sepales.png
├── LICENSE
├── notebooks
│   ├── exploration_donnees_iris.ipynb            # Ajoutez des commentaires comme ceci pour décrire
│   ├── visualisation_donnees_croisees.ipynb
│   └── visualisation_donnees_iris.ipynb
├── pyproject.toml
├── README.md
├── src
│   └── generation_table_jointe.py
├── synthese.ipynb
└── uv.lock
```

## Instructions pour reproduire les résultats du projet

Ne pas hésiter à mettre des instructions en bash directement comme ceci :

```{bash}
git clone https://github.com/username/nom_du_repo.git
cd nom_du_repo
```

Pensez à l'installation des dépendances, ...

N'hésitez pas à vous faire aider par des IAs génératives si vous n'êtes pas familiers avec la mise en page markdown.

Si vous avez des données scrapées, impossibles à recréer, ou longues à récupérer/traiter, mettez-les dans un dossier `diffusion/` de votre bucket s3, il sera par défaut partagé aux autres utilisateurs. 
