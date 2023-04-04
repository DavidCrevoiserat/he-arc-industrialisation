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

# Sur l’onglet Summary d’une analyse de code, SonarCloud fournit 4 indicateurs. Quels sont-ils et quelles sont leurs utilités ?
- Bugs : nombre de bugs détectés par SonarCloud
- Vulnerabilities : nombre de vulnérabilités détectées par SonarCloud
- Code Smells : nombre de code smells détectés par SonarCloud. Un code smell est un code qui n'est pas forcément incorrect, mais qui peut être amélioré.
- Security Hotspots : nombre de hotspots de sécurité détectés par SonarCloud. Un hotspot de sécurité est un code qui peut potentiellement être une faille de sécurité.

# À quoi sert l’indicateur Quality Gate ?
L'indicateur Quality Gate permet de savoir si le projet respecte les règles de qualité définies par l'utilisateur. Il permet de rapidement savoir si le projet peut être déployé en production ou non.

