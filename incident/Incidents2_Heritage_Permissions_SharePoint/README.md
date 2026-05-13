# Incident SharePoint – Héritage des permissions

## Contexte
Ajout de l’utilisateur temp.user comme membre de l’équipe Corporate Hub.

## Observation
Après connexion à SharePoint, l’utilisateur pouvait accéder à tous les documents du site.

## Cause
Les documents héritaient des permissions du site SharePoint lié à l’équipe Teams.

## Risque
Un utilisateur standard peut accéder à des documents sensibles si les permissions ne sont pas restreintes.

## Solution envisagée
Casser l’héritage des permissions et appliquer des droits spécifiques par dossier/document.
