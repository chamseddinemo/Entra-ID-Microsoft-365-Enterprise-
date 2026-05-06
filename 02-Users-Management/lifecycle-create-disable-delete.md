# Cycle de vie utilisateur

## Étapes standard

| Phase | Action dans Entra ID | Vérification |
|-------|----------------------|--------------|
| À l’embauche | Créer utilisateur, affecter groupe(s) et licence(s) | Connexion réussie |
| Mutation | Ajuster groupes / licences | Accès métier OK |
| Congé / suspension | Révoquer sessions, désactiver connexion si besoin | Blocage attendu |
| Départ | Désactiver puis supprimer selon politique | Données / boîtes selon RG |

## Journal des tests effectués

| Utilisateur | Action testée | Résultat | Date |
|-------------|---------------|----------|------|
| IT.USER | Création | Positif | 2026/05/05 |
| IT.USER | Désactivation | Positif | 2026/05/05 |
| IT.USER | Réactivation | Positif | 2026/05/05 |
| IT.USER | Suppression | Positif | 2026/05/05 |
