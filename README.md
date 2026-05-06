# Portfolio Help Desk Microsoft 365 (Office 365)

Projet pratique orienté **poste Help Desk / Support IT** pour montrer un workflow complet dans un environnement Microsoft 365:

- creation et configuration d'un tenant
- gestion des utilisateurs et groupes
- attribution des licences Microsoft 365
- securisation avec MFA et Conditional Access
- resolution d'incidents utilisateurs

Ce depot est ecrit pour etre **simple a lire par un recruteur**: chaque section correspond a une competence terrain, avec preuves visuelles dans un dossier `images/`.

## Profil cible

Ce projet demontre des competences pour:

- Help Desk N1/N2
- Technicien support Microsoft 365
- Junior IT Administrator (M365)

## Competences demontrees

- Administration des comptes utilisateurs (creation, reset mot de passe, blocage/deblocage)
- Gestion des groupes et de l'acces par role
- Attribution/retrait de licences Microsoft 365
- Application de MFA et politiques Conditional Access
- Diagnostic et resolution d'incidents courants
- Documentation claire et communication support

## Navigation rapide (version recruteur)

| Section | Objectif metier |
|---------|-----------------|
| [00-Project-Overview](00-Project-Overview/objectives.md) | Contexte, objectifs, perimetre du role Help Desk |
| [01-Tenant-Setup](01-Tenant-Setup/tenant-creation.md) | Mise en place de l'environnement Microsoft 365 |
| [02-Users-Management](02-Users-Management/users-created.md) | Gestion du cycle de vie des utilisateurs |
| [03-Groups-Management](03-Groups-Management/groups-structure.md) | Organisation des groupes et droits d'acces |
| [04-Licensing-Microsoft365](04-Licensing-Microsoft365/license-assignment.md) | Gestion des licences Microsoft 365 |
| [05-MFA-ConditionalAccess](05-MFA-ConditionalAccess/mfa-setup.md) | Securisation des connexions |
| [06-Security-Roles](06-Security-Roles/role-assignment.md) | Delegation de roles admin avec moindre privilege |
| [07-Helpdesk-Scenarios](07-Helpdesk-Scenarios/scenario-01-login-issue.md) | Cas reels de tickets Help Desk |
| [08-Troubleshooting-Guide](08-Troubleshooting-Guide/decision-tree.md) | Methodologie de depannage |
| [09-Logs-Screenshots-Evidence](09-Logs-Screenshots-Evidence/README.md) | Journal des actions + preuves |
| [10-Optional-Automation](10-Optional-Automation/README.md) | Automatisation (bonus) |

## Ce que doit voir un recruteur rapidement

1. **Probleme support** -> 2. **Analyse** -> 3. **Resolution** -> 4. **Preuve (capture)** -> 5. **Bonne pratique**

Chaque dossier contient:

- des fichiers `.md` avec la procedure
- un dossier `images/` pour les captures d'ecran de la section

## Structure des preuves visuelles

Convention conseillee pour nommer les captures:

- `01-portail-admin-overview.png`
- `02-user-created-success.png`
- `03-license-assigned-e3.png`
- `04-mfa-challenge-policy.png`
- `05-ticket-login-resolved.png`

## Environnement technique

- Microsoft 365 Admin Center
- Microsoft Entra Admin Center
- Exchange Admin Center (si utilise)
- MFA / Conditional Access
- RBAC Entra ID

## Note

Ce repository est volontairement axe sur les operations **Office 365 / Microsoft 365** utiles au quotidien d'un Help Desk.  
Pense a remplir les valeurs reelles (UPN, groupes, SKU de licence, nom des policies) apres chaque manipulation.
