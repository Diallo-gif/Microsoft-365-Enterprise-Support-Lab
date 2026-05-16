# Incident 7 — OneDrive inaccessible après désactivation du compte

## Problème

Le compte `lina.finance` a été désactivé dans Microsoft Entra ID.

Après la désactivation :
- OneDrive devient inaccessible
- erreurs d’authentification Microsoft 365
- impossibilité d’accéder aux fichiers cloud

---

## Analyse

Vérification :
- état du compte dans Entra ID
- accès aux services Microsoft 365
- dépendance entre identité et services cloud

Constat :
- le compte désactivé bloque automatiquement l’accès aux services liés

---

## Résolution

- réactivation du compte utilisateur
- reconnexion Microsoft 365
- validation de l’accès OneDrive

Résultat :
- OneDrive fonctionne de nouveau normalement

---

## Compétences travaillées

- Microsoft Entra ID
- Gestion des identités
- OneDrive
- Authentification Microsoft 365
- Diagnostic cloud
