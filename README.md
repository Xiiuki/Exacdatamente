
# EXACDATAMENTE E-COMMERCE ANALYSE (FEB 2020)


![plot](./IMGS/README/intro.png)

--------------------------
### [PDF Synthese version](Project_Exacdatamente.pdf) | [GitHub version](https://github.com/Xiiuki/Exacdatamente) | [GitLab version](https://gitlab.com/Xiiuki/exacdatamente/-/tree/Matthias) | [Google Drive](https://drive.google.com/drive/folders/1WODaQX4J4sFKTi9mP-UcTSm8uPfq-te_)
## <br> Colab : <br/>

   - Vincent Lhoste
    
   - [Corentin Pingeon](https://www.linkedin.com/in/corentin-pingeon-1a7a251b0/)
    
   - [Jonhatan Groegen](https://www.linkedin.com/in/jonathan-goergen/)
    
## <br> Note : <br/>

Analyse de deux dataset fournis par un client E-commerce.

Objectif de traitement des dataset, création d'une database et analyse pour fournir un dashboard 

## <br> Livrables <br/> 


--------

    ├── README.md
    │
    │
    ├── BDD
    │   ├── Brut_csv       
    │   ├── Final_csv      
    │   └── Query_csv      
    │
    ├── IMGS               
    │   ├── Analyse
    │   ├── README
    │   └── UML
    │
    ├── Jinja2             
    │   ├── html
    │   │   ├── index.html
    │   │   └── img
    │   │      
    │   └── templates
    │       └── index.html
    │
    ├── Analyse_csv.ipynb    
    │                                               
    │
    ├── Traitement_csv.ipynb        
    │
    │
    ├── Database.ipynb         
    │                          
    │
    ├── Vizualisation.ipynb 
    │
    │
    ├── Dashboard_Jinja2.ipynb                                        
    │    
    │
    ├── Analyse_csv_pdf.pdf
    │
    │
    ├── mock_up.pdf
    │
    │
    ├── Project_Exacdatamente.pdf
    │
    │
    ├── requirements.txt
    │
    │
    └── UML.mdj
--------
   
## <br> Requirements : <br/>

    - Les scripts sont testés sous Windows 10 
    - python 3.8.6 + requirements
    - postgreSQL
    - pgAdmin 4 
    - StarUML pour la lecture du fichier .mdj (https://staruml.io/download)
    
## <br>Installation : <br/>

Dans un premier temps, l'installation de postgresql et pgadmin est nécéssaire :

Suivre les étapes indiquées :

  - https://www.postgresql.org/download/ (download)

  - https://www.veremes.com/installation-postgresql-windows (isntallation)
  

Puis pour terminer, le clone du projet et sa bonne installation sur votre pc :

 - Le clonage :

    ```
    cd c:/
    mkdir Projet
    cd Projet
    git clone https://
    cd exacdatamente
    ```
 
 - Création de l'environnement virtuelle :
 
    ```
    python -m venv *nom_env*
    source *nom_venv*/Scripts/activate
    ```
     
     
 - Installation des librairies :
    
    ```
    python -m pip install pip --upgrade
    pip install requirements.txt
    pip freeze
    ```
    
 - Lancer le notebook :
    
    ```
    jupyter-lab
    ```
    
    
    
## <br> Exécution projet : <br/>

Tout d'abord exécuter [Traitement_csv](02_Traitement_csv.ipynb)

Ensuite exécuter les cellules sur [Database](03_Database.ipynb)

Puis [Vizualisation SQL](04_Vizualisation_SQL.ipynb), lancer jinja2 [DashBoard_Jinja2](05_Dashboard_Jinja2.ipynb) et ouvrir le [Dashboard](Jinja2/html/index.html)
