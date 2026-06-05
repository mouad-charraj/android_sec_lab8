# Notes d'analyse Yaazhini

## Rapport
- Le rapport Yaazhini a ete consulte pendant le lab.
- Les preuves visuelles sont conservees dans `screens/Capture d'écran 2026-06-01 095324.png` et `screens/Capture d'écran 2026-06-01 095334.png`.

## Ce qui est certain
- L'APK `UnCrackable-Level1.apk` a ete analysee avec Yaazhini.
- Le tableau de resultats et la synthese de risque ont ete observes.
- Les resultats sont utilises pour alimenter le triage statique.

## Manifest Android
- Le manifest est considere comme un point de verification principal pour les permissions, les composants et les options de configuration Android.

## Reseau
- Aucun flux reseau sensible n'est confirme dans les preuves conservees.
- Les elements reseau restent classes RAS dans le triage.

## Stockage et secrets
- Aucun secret exploitable n'est confirme dans les preuves conservees.
- La verification du stockage reste rattachee a MASVS-STORAGE dans le mapping OWASP.

## Code et resilience
- L'application etant un crackme pedagogique OWASP, les controles de resilience et de reverse engineering sont consideres comme une zone importante de lecture.
- Les observations de resilience sont rattachees a MASVS-RESILIENCE dans le mapping OWASP.
