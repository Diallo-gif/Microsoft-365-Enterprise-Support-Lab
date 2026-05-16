
# Incident 3 — Utilisateur visible dans Teams mais sans accès SharePoint

## Problème

L’utilisateur `guest.partner` voit l’équipe Teams `Finance` mais ne peut pas ouvrir les fichiers SharePoint.

Message affiché :
- `Accès requis / Access Denied`

---

## Analyse

Vérification :
- appartenance à l’équipe Teams
- permissions SharePoint
- héritage des autorisations

Constat :
- l’utilisateur était membre Teams mais ne possédait pas les autorisations SharePoint nécessaires.

---

## Résolution

- contrôle des permissions SharePoint
- analyse des groupes Microsoft 365
- test avec le compte `guest.partner`

Résultat :
- accès SharePoint bloqué pour les utilisateurs non autorisés
- sécurisation des documents du site Teams

---

## Compétences travaillées

- Microsoft Teams
- SharePoint Online
- Permissions Microsoft 365
- Héritage des autorisations
- Diagnostic d’accès utilisateur
