# Entra-ID-Microsoft-365-Enterprise-
Entra ID &amp; Microsoft 365 Enterprise 

<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="UTF-8">
<title>Entra ID & Microsoft 365 Enterprise Lab</title>
</head>
<body>

<h1>🧪 Entra ID & Microsoft 365 Enterprise Lab</h1>

<h2>📁 Repository Structure 📸</h2>
👉 📸 Screenshot : structure GitHub du repo

<pre>
EntraID-M365-Enterprise-Lab/
│
├── README.md
│
├── 00-Project-Overview/
│   ├── architecture-diagram.png
│   ├── objectives.md
│   ├── environment-setup.md
│
├── 01-Tenant-Setup/
│   ├── tenant-creation.md
│   ├── issues-encountered.md
│   ├── screenshots/
│
├── 02-Users-Management/
│   ├── users-created.md
│   ├── user-roles-table.md
│   ├── lifecycle-create-disable-delete.md
│   ├── screenshots/
│
├── 03-Groups-Management/
│   ├── groups-structure.md
│   ├── membership-mapping.md
│   ├── owners-configuration.md
│   ├── screenshots/
│
├── 04-Licensing-Microsoft365/
│   ├── license-assignment.md
│   ├── license-removal.md
│   ├── license-impact-analysis.md
│   ├── screenshots/
│
├── 05-MFA-ConditionalAccess/
│   ├── mfa-setup.md
│   ├── conditional-access-policy.md
│   ├── testing-mfa.md
│   ├── screenshots/
│
├── 06-Security-Roles/
│   ├── role-assignment.md
│   ├── helpdesk-admin-role.md
│   ├── role-comparison.md
│   ├── screenshots/
│
├── 07-Helpdesk-Scenarios/
│   ├── scenario-01-login-issue.md
│   ├── scenario-02-mfa-block.md
│   ├── scenario-03-license-missing.md
│   ├── scenario-04-group-access.md
│   ├── scenario-05-account-disabled.md
│
├── 08-Troubleshooting-Guide/
│   ├── decision-tree.md
│   ├── common-errors.md
│   ├── resolution-steps.md
│
├── 09-Logs-Screenshots-Evidence/
│   ├── users/
│   ├── groups/
│   ├── mfa/
│   ├── licensing/
│   ├── errors/
│
└── 10-Optional-Automation/
   ├── powershell-users.ps1
   ├── powershell-groups.ps1
   ├── license-check.ps1
</pre>

---

<h2>📘 README 📸</h2>
👉 📸 Screenshot : README affiché sur GitHub

<pre>
# 🧪 Entra ID & Microsoft 365 Enterprise Lab

## 🎯 Objective
This project simulates a real IT Help Desk / Junior Azure Administrator environment using Microsoft Entra ID and Microsoft 365.

## 🧰 Technologies
- Microsoft Entra ID
- Microsoft 365
- Conditional Access
- MFA (Multi-Factor Authentication)
- Role-based Access Control (RBAC)

## 🏢 Scenario
The environment simulates a small company with departments:
- IT
- HR
- Finance
- Training (TR)

## 🧱 Core Concepts Covered
- User lifecycle management
- Group-based access control
- License management
- MFA implementation
- Security roles assignment
- Help desk troubleshooting

## 🧪 Key Skills Demonstrated
- Identity management
- Access control
- Security configuration
- Incident troubleshooting
- IT support scenarios
</pre>

---

<h2>🧠 Architecture Logic 📸</h2>
👉 📸 Screenshot : diagram logique (users → groups → access)

<pre>
Users → Groups → Licenses → Roles → Access
           ↓
    Conditional Access (MFA)
</pre>

---

<h2>👥 Enterprise Structure 📸</h2>
👉 📸 Screenshot : users + groupes dans Entra ID

<table border="1">
<tr>
<th>Department</th>
<th>User</th>
<th>Group</th>
<th>License</th>
<th>Role</th>
</tr>
<tr>
<td>IT</td>
<td>ItUser</td>
<td>IT</td>
<td>✔</td>
<td>Helpdesk Admin</td>
</tr>
<tr>
<td>HR</td>
<td>RhUser</td>
<td>HR</td>
<td>✔</td>
<td>❌</td>
</tr>
<tr>
<td>Finance</td>
<td>financeuser</td>
<td>Finance</td>
<td>✔</td>
<td>❌</td>
</tr>
<tr>
<td>TR</td>
<td>TrUser</td>
<td>TR</td>
<td>✔</td>
<td>❌</td>
</tr>
</table>

---

<h2>🔐 MFA (Conditional Access) 📸</h2>
👉 📸 Screenshot : policy MFA configurée

<ul>
<li>All users or IT group</li>
<li>Require MFA</li>
<li>All cloud apps</li>
</ul>

---

<h2>🧪 Helpdesk Scenarios 📸</h2>
👉 📸 Screenshot : exemples incidents / résolution

<ul>
<li>Login issue → reset password</li>
<li>MFA blocked → reset MFA</li>
<li>No license → assign Microsoft 365 license</li>
<li>No access → fix group membership</li>
<li>Account disabled → enable sign-in</li>
</ul>

---

<h2>🚨 Troubleshooting Flow 📸</h2>
👉 📸 Screenshot : flow troubleshooting (diagram ou notes)

<pre>
Issue → Identify → Check (User / Group / License / MFA) → Fix → Test → Resolve
</pre>

</body>
</html>
