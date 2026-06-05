# Mapping OWASP

## FIND-003: Scan externe consulte
- Categorie OWASP: MASVS-CODE
- Reference specifique: controle de qualite et d'exposition du code applicatif
- Justification: BeVigil sert a relever des signaux publics associes a l'application avant validation manuelle.

## FIND-006: Manifest Android retenu comme zone de controle
- Categorie OWASP: MASVS-PLATFORM
- Reference specifique: interaction avec la plateforme Android
- Justification: le manifest contient les permissions, composants et declarations qui influencent la surface d'exposition.

## FIND-007: Aucun endpoint sensible confirme
- Categorie OWASP: MASVS-NETWORK
- Reference specifique: communications reseau
- Justification: les endpoints et URLs sont controles pour verifier l'absence d'exposition reseau confirmee dans les preuves.

## FIND-008: Aucun secret exploitable confirme
- Categorie OWASP: MASVS-STORAGE
- Reference specifique: stockage de donnees sensibles
- Justification: les notes Yaazhini conservent la verification du stockage et des secrets comme point de controle.

## FIND-010: Resilience identifiee comme axe de lecture
- Categorie OWASP: MASVS-RESILIENCE
- Reference specifique: resistance au reverse engineering et a la modification
- Justification: la cible est un crackme pedagogique OWASP et les controles de resilience font partie du contexte d'analyse.
