# Incident 8 — Permissions cassées après déplacement d’un document

## Problème

Un document RH confidentiel a été déplacé depuis un canal privé Teams vers la bibliothèque principale SharePoint de l’équipe Finance.

Après déplacement, les permissions du document ont changé.

---

## Analyse

- vérification des permissions SharePoint
- contrôle de l’héritage des autorisations
- comparaison entre canal privé et bibliothèque principale

Constat :
le déplacement du fichier a modifié les permissions héritées.

---

## Résolution

- réintégration du document dans le canal privé
- validation des accès utilisateurs
- contrôle des permissions sensibles

Résultat :
les accès redeviennent limités aux membres autorisés.
