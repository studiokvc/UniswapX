# 1. Présentation et architecture

UniswapX règle des ordres de swap ERC-20 signés avec des reactors et des fillers. Le parcours suit la validation de l’ordre, le transfert témoin via Permit2, le callback de remplissage et la remise des sorties. Ce chapitre isole le mécanisme correspondant dans les contrats et bibliothèques du dépôt : état conservé, appels, contrôles et invariant attendu. Les explications restent documentaires et ne constituent ni un audit ni une garantie de déploiement.

[Chapitre suivant →](02-chapitre.md)
