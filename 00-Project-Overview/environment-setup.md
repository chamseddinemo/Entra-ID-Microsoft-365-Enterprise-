# Environnement et prérequis

## Prérequis compte Microsoft

| Élément | Détail à renseigner |
|---------|---------------------|
| Type de tenant | Ex. Microsoft Entra ID gratuit / essai M365 |
| Compte administrateur global | `___________________________` |
| Licence d’évaluation | SKU utilisée : `___________________________` |

## Outils recommandés

| Outil | Usage |
|-------|--------|
| Portail Entra admin | Utilisateurs, groupes, licences, CA |
| Portail Microsoft 365 admin | Services collaboratifs |
| Microsoft Graph Explorer (optionnel) | Vérification API |

## Schéma d’architecture

Placez votre fichier diagramme ici : `architecture-diagram.png` (à la racine de ce dossier).

| Composant | Rôle dans le lab |
|-----------|-------------------|
| Entra ID | Source d’identité |
| Groupes | Agrégation des droits |
| Licences | Activation des workloads |
| CA | Exigences d’accès (MFA, etc.) |
