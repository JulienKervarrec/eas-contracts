# 1. Vue d’ensemble d’EAS

Ethereum Attestation Service est un protocole ouvert d’attestations sur des chaînes compatibles EVM. Un émetteur enregistre d’abord un schéma dans SchemaRegistry, puis crée une attestation structurée dans EAS.

Le modèle sépare la définition des champs, l’enregistrement de l’attestation, les règles de résolution et la lecture indexée. Il convient à l’identité, à la réputation, au financement, au vote et à de nombreux usages où une déclaration vérifiable doit rester portable.

Ce parcours suit Common.sol, IEAS, EAS.sol, SchemaRegistry.sol, les résolveurs, la délégation EIP-712 et Indexer.sol. Il décrit le code lu statiquement, sans promettre une sécurité ou une validité métier.

Suite : [enregistrer un schéma](02-schemas.md).
