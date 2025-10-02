# Task 7 — Identify and Remove Suspicious Browser Extensions

## Objective
The objective of this task was to identify potentially suspicious browser extensions, review their permissions and behavior, and remove them if necessary. This helps in understanding browser security risks and managing extensions effectively.

## Browser Used
- **Google Chrome**

## Steps Performed
1. Opened the Chrome extensions manager (`chrome://extensions/`).
2. Reviewed installed extensions and their details:
   - Checked publisher, permissions, and site access.
   - Verified official sources and update history.
3. Found the extension **Grammarly: AI Writing Assistant and Grammar Checker App**.
4. Analyzed its permissions:
   - Can read browsing history.
   - Can display notifications.
   - Has access to read/change all data on websites.
5. Although Grammarly is a trusted and widely used tool, I removed it for practice and documentation purposes in this task.
6. Captured **before** and **after** screenshots for evidence.
7. Documented removal in `extensions_removed.md`.


## Extension Removed
| Name        | Publisher     | Version    | Permissions | Reason Removed | Action |
|-------------|--------------|------------|-------------|----------------|--------|
| Grammarly: AI Writing Assistant and Grammar Checker App | Grammarly, Inc. | 14.1256.0 | - Read browsing history<br>- Display notifications<br>- Full data access on all sites | Removed as part of the security awareness exercise (even though it is safe, it has high-level permissions). | Removed |

## Evidence
- `screenshots Before_Extensions.png` — Extensions before removal.  
- `screenshots After_Remove_Extension.png` — Proof of Grammarly removal.  
- `Extensions_Removed.md` — Detailed log of reviewed/removed extensions.


## Key Learnings
- Extensions may request broad permissions such as “Read and change all your data on websites you visit,” which can be risky.  
- Even popular extensions like Grammarly require sensitive permissions, highlighting the need to review them carefully.  
- It is good practice to remove unused or unnecessary extensions to reduce the attack surface.  
- Browser security requires continuous monitoring and awareness.


## Files in this Repo
- `README.md` — Documentation of Task 7.  
- `extensions_removed.md` — Detailed log of extensions reviewed and removed.  
- `screenshots` — Contains before/after evidence.
