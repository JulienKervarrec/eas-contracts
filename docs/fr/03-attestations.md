# 3. Création et lecture d’une attestation

EAS reçoit une AttestationRequest contenant le schéma, le destinataire, les dates, la révocabilité et les données ABI encodées. La fonction attest calcule un identifiant, stocke la structure et émet l’événement destiné aux lecteurs et indexeurs.

multiAttest regroupe plusieurs créations pour réduire le coût d’intégration. L’attestation conserve notamment l’émetteur, le destinataire, le schéma, le timestamp, la date d’expiration, le lien éventuel vers une attestation et la charge utile.

Une application doit vérifier le schéma attendu, le type du destinataire et les dates avant d’accorder une confiance économique à une attestation.

Suite : [révocation et temporalité](04-revocation.md).
