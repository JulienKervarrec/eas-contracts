# 4. Révocation, expiration et temporalité

Une attestation peut être révocable selon le drapeau du schéma. L’émetteur appelle revoke pour la marquer révoquée ; l’opération ne réécrit pas la déclaration initiale mais change son état consultable.

Les dates d’émission et d’expiration permettent de distinguer une information encore valide d’une information historique. EAS expose aussi une temporalité pour certaines données hors chaîne et un mécanisme de révocation hors chaîne.

Le contrat vérifie les droits de l’émetteur et les paramètres de révocabilité. Le consommateur doit toutefois décider ce que signifie une expiration pour son propre domaine.

Suite : [résolveurs et règles métier](05-resolveurs.md).
