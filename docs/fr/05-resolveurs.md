# 5. Résolveurs et règles métier

Un SchemaResolver reçoit les callbacks attest, multiAttest et revoke depuis EAS. Il peut refuser une attestation ou appliquer une logique métier complémentaire, par exemple contrôler un destinataire, enregistrer une preuve ou gérer un paiement.

Les exemples incluent des résolveurs liés à l’attestation, à l’attester, à l’expiration, à la révocation, aux tokens et à la valeur. La restriction onlyEAS empêche un appel arbitraire qui contournerait le cycle principal.

Un résolveur élargit la surface d’exécution et peut déplacer des fonds. Il faut donc analyser ses retours, ses reverts, ses autorisations et ses éventuels appels externes.

Suite : [délégation et signatures](06-delegation.md).
