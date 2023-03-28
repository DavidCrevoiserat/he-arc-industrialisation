# Quelles étapes sont réalisées par cette action ?
- Récupération du code source
- Configuration de la version de Python
- Installation des dépendances à partir du fichier requirements.txt
- Vérification de la qualité du code avec Flake8
- Exécution des tests avec pytest

# Une étape est définie au minimum par 2 paramètres, lesquels sont-ils et à quoi servent-ils ?
- `name` : le nom de l'étape qui apparaîtra dans les logs
- `run` : les commandes à exécuter

# La première étape contient un paramètre ‘with’, a quoi sert-il ?
Cela permet de transmettre des arguments à l'action setup-python (dans notre cas la version de Python)


# Token
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