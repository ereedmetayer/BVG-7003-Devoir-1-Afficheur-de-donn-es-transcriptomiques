# BVG-7003 Devoir-1 Afficheur de données transcriptomiques

Cas d'utilisation : L'objectif du script est d'identifer les différences d'expression génique graphiquement à partir d'un jeu de données de transcriptomique. Le script est construit avec en exemple une paire de gènes et une seule variable catégorique de comparaison.

Données d'entrée : Dans son état original, ce script utilise des données de transcriptomique sous format .csv, où les IDs de gènes sont en rangées et où les échantillons sont en colonnes. Une information additionnelle concernant les échantillons (par exemple pour ajouter une variable servant de catégorie de comparaison) doit faire partie du nom de l'échantillon en suffixe (après un underscore "_"). Le script dans son état original est construit pour que cette information soit le sexe du plant de cannabis échantillonné. 

Résultats : Le script génère trois graphiques de type boxplot pour comparer l'expression génique normalisée de manière comparative entre catégories. Dans le script original, les catégories correspondent au sexe de plants de cannabis échantillonnés et illustre l'expression génique normalisée de deux gènes tel qu'obtenue par par analyse du transcriptome (RNAseq), soit REM16 et FT1.

Instructions : Ouvrez le script dans l'interface R de votre choix, par exemple Rstudio et téléchargez le fichier 2_Data_RNASeq_Cannabis_Sex.csv. Vous devrez ajuster le chemin vers le jeu de données propre à votre ordinateur. Des informations additionnelles pour chaque étape plus en détails sont annotées dans le script.

