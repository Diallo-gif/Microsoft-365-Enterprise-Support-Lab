# Incident Teams après réinitialisation du mot de passe

## Contexte
Simulation d’un utilisateur Microsoft 365 dont le mot de passe a été réinitialisé dans Entra ID.

## Actions réalisées
- Disable account
- Enable account
- Reset password
- Revoke Sessions
- Test de connexion Teams Web/Desktop

## Comportement observé
Même après la réinitialisation du mot de passe, Teams conservait parfois une ancienne session active.

## Résolution
1. Connexion via Teams Web
2. Déconnexion complète de la session active
3. Reconnexion dans l’application Teams avec le nouveau mot de passe

## Technologies utilisées
- Microsoft Entra ID
- Microsoft Teams
- Microsoft 365
