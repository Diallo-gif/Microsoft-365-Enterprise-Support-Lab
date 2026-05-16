# Incident 5 — Outlook disparaît après modification de licence

## Problème

L’utilisateur `guest.partner` ne pouvait plus utiliser Outlook après une modification de licence Microsoft 365.

Cependant, Microsoft Teams restait accessible.

---

## Analyse

Vérification :
- licences Microsoft 365
- services attribués à l’utilisateur
- accès Teams et Outlook

Constat :
- la licence `Exchange Online (Plan 1)` avait été désactivée.

---

## Résolution

- analyse des licences Microsoft 365
- vérification des services impactés
- test de connexion utilisateur

Résultat :
- Teams restait fonctionnel
- Outlook devenait indisponible sans Exchange Online

---

## Compétences travaillées

- Microsoft 365
- Exchange Online
- Gestion des licences
- Diagnostic utilisateur
- Dépendances des services Microsoft 365
