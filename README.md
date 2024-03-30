# Skin Dataset
Dataset constitué dans le cadre du Devoir 3 du cours [INF889G Vision par ordinateur](http://info.uqam.ca/INF889X/) [Hiver 24] de l'Université du Québec à Montréal.

## Composition
Le jeu de données se compose d'images d'affections cutanées.  
Les affections considérées sont :
- Acné
- Rougeole
- Piqures de moustiques

> **Avertissement sur la qualité des données:** le dataset n'a pas été vérifié par un professionnel de la santé, certaines étiquettes pourraient être incorrectes.

## Architecture

```
.
└── dataset/
    ├── README.md
    ├── training/
    │   ├── acne/
    │   │   ├── image_1.jpg
    │   │   └── ...
    │   ├── measles/
    │   │   ├── image_1.jpg
    │   │   └── ...
    │   └── mosquito_bite/
    │       ├── image_1.jpg
    │       └── ...
    └── validation/
        └── ...
```

## Provenance des données
Les données proviennent de diverses sources en ligne, exhaustivement :
- Acné
    - UK NHS (https://www.nhs.uk/)
    - Ducray (https://www.ducray.com)
    - Dermato Info (https://dermato-info.fr)
    - Manhattan Dermatology (https://www.dermatologistnewyork.org)
    - Cleveland Clinic (https://my.clevelandclinic.org)
    - DestinationSanté (https://destinationsante.com)
    - 20Minutes (https://www.20minutes.fr)
    - Roshu Bangal / Wikipedia


- Rougeole
    - US CDC (https://cdc.gov)
    - Scotland NHS (https://nhsinform.scot)
    - The Hospital for Sick Children (https://www.aboutkidshealth.ca)
    - GPOnline (https://gponline.com)
    - Irish Examiner (https://irishexaminer.com)
    - Everyday Health (https://www.everydayhealth.com)
- Piqures de moustiques
    - Bjørn-Jostein Singstad / Kaggle
    - Nextgen Pest Solutions (https://ngpest.com)
    - EnviroPest (https://www.enviropest.com)
    - Illinois Natural History Survey (https://drs.illinois.edu)
    - ProjectManhattan / Wikipedia

Méthodologie de collecte : téléchargement à partir d'internet (recherche de mots clés sur [Google Image](https://images.google.com/)).