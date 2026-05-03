# Entra ID & Microsoft 365 Enterprise Lab

Laboratoire documenté : tenant Entra ID, utilisateurs, groupes, licences, MFA / Conditional Access, rôles et scénarios helpdesk.

## État du dépôt vs README

| Élément | Avant | Maintenant |
|--------|-------|------------|
| Arborescence décrite dans le README | Oui (schéma uniquement) | Dossiers et fichiers `.md` présents |
| Captures / preuves | Références « 📸 » | Dossiers `screenshots/` et `09-Logs-Screenshots-Evidence/` prêts à recevoir les fichiers |
| Tableaux métier | Partiels dans le README | Tableaux dédiés par section |

## Navigation rapide

| Section | Contenu |
|---------|---------|
| [00-Project-Overview](00-Project-Overview/objectives.md) | Objectifs, prérequis |
| [01-Tenant-Setup](01-Tenant-Setup/tenant-creation.md) | Création tenant, problèmes rencontrés |
| [02-Users-Management](02-Users-Management/users-created.md) | Utilisateurs, cycle de vie |
| [03-Groups-Management](03-Groups-Management/groups-structure.md) | Groupes, appartenances |
| [04-Licensing-Microsoft365](04-Licensing-Microsoft365/license-assignment.md) | Attribution / retrait licences |
| [05-MFA-ConditionalAccess](05-MFA-ConditionalAccess/mfa-setup.md) | MFA et CA |
| [06-Security-Roles](06-Security-Roles/role-assignment.md) | Rôles administrateur |
| [07-Helpdesk-Scenarios](07-Helpdesk-Scenarios/scenario-01-login-issue.md) | Cas support |
| [08-Troubleshooting-Guide](08-Troubleshooting-Guide/decision-tree.md) | Dépannage |
| [09-Logs-Screenshots-Evidence](09-Logs-Screenshots-Evidence/README.md) | Preuves / captures |
| [10-Optional-Automation](10-Optional-Automation/README.md) | Placeholder automation (sans scripts fournis ici) |

## Objectif du projet

Simulation d’un environnement **helpdesk / administrateur junior** avec Microsoft Entra ID et Microsoft 365.

## Technologies

- Microsoft Entra ID  
- Microsoft 365  
- Conditional Access  
- MFA  
- RBAC Entra  

## Entreprise fictive (départements)

IT · RH · Finance · Travaux publics (TR)

## Chaîne logique d’accès

```
Utilisateurs → Groupes → Licences → Rôles → Accès
                      ↓
         Conditional Access (MFA)
```

## Structure du dépôt

Voir les dossiers numérotés `00-` à `10-` à la racine ; chaque dossier contient des fichiers Markdown et des sous-dossiers `screenshots/` lorsque des captures sont attendues.

---

*Complétez les tableaux avec vos valeurs réelles (UPN, IDs de groupe, noms de stratégies CA, etc.) après chaque étape du lab.*
