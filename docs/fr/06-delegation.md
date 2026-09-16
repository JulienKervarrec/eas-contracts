# 6. Délégation et signatures EIP-712

EAS et EIP712Proxy permettent de soumettre certaines attestations ou révocations au nom d’un signataire. La signature encode le domaine, la requête et un nonce afin d’éviter la réutilisation d’un message.

Le proxy sépare la vérification de la signature de l’appel vers EAS. Des variantes permissionnées peuvent restreindre les schémas ou les signataires autorisés.

La délégation ne supprime pas les contrôles de validité : chaîne, domaine EIP-712, nonce, expiration et destinataire doivent être cohérents. Une intégration doit aussi traiter les signatures de contrats via EIP-1271.

Suite : [indexation et déploiements](07-indexation.md).
