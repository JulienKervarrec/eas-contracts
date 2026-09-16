# 2. Schémas et identifiants

SchemaRegistry enregistre une chaîne de schéma, un résolveur optionnel et le caractère révocable ou non des attestations. L’identifiant du schéma est dérivé de son contenu et de ses paramètres, ce qui permet de référencer une définition de façon compacte.

Le schéma décrit les types et l’ordre des données encodées. Une application doit donc conserver la même interprétation lors de l’encodage et de la lecture ; changer le texte du schéma crée une nouvelle identité logique.

Le registre ne valide pas la pertinence sémantique d’un schéma. La qualité dépend de champs non ambigus, de versions explicites et d’un contrôle des résolveurs associés.

Suite : [créer et lire une attestation](03-attestations.md).
