# Incident 4 — Administrateur ayant accès à des documents sensibles

## Problème

Le compte `support.audit` pouvait accéder à des documents RH sensibles dans le site SharePoint `HR Département`.

Le service RH considère cet accès comme un risque de gouvernance et de confidentialité.

---

## Analyse

Vérification :
- rôles administratifs
- appartenance aux groupes Microsoft 365
- permissions SharePoint
- accès aux documents confidentiels

Constat :
- le compte `support.audit` possédait des privilèges élevés permettant l’accès aux documents RH.

---

## Résolution

- analyse des permissions du site
- contrôle des accès administratifs
- vérification des groupes et rôles associés

Résultat :
- identification des accès excessifs
- amélioration de la gouvernance des documents sensibles

---

## Compétences travaillées

- Microsoft 365
- SharePoint Online
- Gouvernance des accès
- Permissions administratives
- Sécurité documentaire
