# Rapport final - Lab Mobile Security

## 1. Perimetre

Cible: OWASP MSTG UnCrackable Level 1
Artefact: 00-scope/UnCrackable-Level1.apk
Hash SHA-256: 1DA8BF57D266109F9A07C01BF7111A1975CE01F190B9D914BCD3AE3DBEF96F21
Cadre: TP de securite mobile sur APK pedagogique autorisee

## 2. Methodologie

- Definition du perimetre et conservation de l'APK dans `00-scope`.
- Calcul du hash SHA-256 pour identifier l'artefact.
- Consultation du resultat BeVigil.
- Consultation du rapport Yaazhini.
- Consolidation des observations dans `03-triage/triage.csv`.
- Correlation des points retenus avec les categories OWASP MASVS.

## 3. Resume des constats

- Le perimetre est documente et limite a l'APK autorisee.
- L'artefact est identifie par un hash SHA-256.
- BeVigil fournit une vue externe de la cible.
- Yaazhini fournit une vue statique de l'APK.
- Aucun endpoint sensible, secret exploitable ou email sensible n'est confirme dans les preuves conservees.
- Le manifest Android et la resilience restent les zones principales de controle pour cette cible pedagogique.

## 4. Recommandations

- Conserver le hash et le scope avec le rendu final.
- Ne pas transformer les alertes d'outils en vulnerabilites sans preuve.
- Garder les resultats BeVigil et Yaazhini comme preuves de collecte.
- Relier chaque observation importante a une categorie OWASP pertinente.
- Maintenir une separation claire entre observation, RAS et vulnerabilite confirmee.

## 5. Limites

L'analyse est limitee a l'APK pedagogique autorisee. Aucun test intrusif, aucune exploitation et aucun ciblage hors perimetre n'ont ete realises.
