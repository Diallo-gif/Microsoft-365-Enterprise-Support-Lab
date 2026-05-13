# Incident 1 – Accès SharePoint refusé malgré un compte administrateur

## Problème

Le compte administrateur `OumarCherifDiallo` ne pouvait pas accéder au site SharePoint de l’équipe privée **Finance**.

> Accès requis – Vous n’avez pas accès à cet élément.

---

## Analyse

Le propriétaire de l’équipe (`lina.finance`) contrôlait réellement l’accès au site SharePoint.

Être administrateur Microsoft 365 ne donnait pas automatiquement accès aux données privées du site.

---

## Test

Je me suis ajouté volontairement comme propriétaire de l’équipe depuis le centre d’administration Microsoft 365.

Résultat :
- accès SharePoint immédiatement obtenu ;
- accès aux documents sensibles possible.

---

## Risque identifié

Un administrateur peut techniquement s’ajouter comme propriétaire d’une équipe privée et accéder à des données sensibles.

Cela montre l’importance :
- du contrôle des rôles administrateurs ;
- des audits ;
- et du principe du moindre privilège.
