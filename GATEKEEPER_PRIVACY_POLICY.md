# GATEKEEPER PRIVACY POLICY
**Effective Date:** November 3, 2026
**Provider:** WinterGate Intelligence Collective (WIC)
**Bot:** GateKeeper / CYRA Gatekeeper

---

## 1. OVERVIEW
This Privacy Policy explains how WinterGate Intelligence Collective ("WIC", "we", "us") collects, uses, stores, and shares data through the GateKeeper Discord bot ("the Bot"). 

Because GateKeeper is a multi-tenant defense network, strict data isolation and transparency are core to our architecture. This policy outlines how we protect your server's data while simultaneously maintaining a global threat intelligence network.

## 2. INFORMATION WE COLLECT

**A. Server & Configuration Data**
- **Guild ID:** Used to strictly isolate your server's configuration from others. We do not cross-contaminate server settings.
- **Channel IDs:** Used to identify where verification codes and reports should be posted.
- **Role IDs:** Used to grant the correct authenticated roles after a user passes the verification flow.

**B. User Data**
- **User ID:** Collected when a user initiates the authentication flow (Stages 1-4) to track their progress and assign roles.
- **Auth Data:** Any answers provided during verification (e.g., Stage 2 questions, Stage 3 review details).
- **Server Membership Status:** To determine if a user is currently in your server or has left.

**C. Threat Intelligence & Reporting Data**
- **IP Addresses:** Submitted via reporting channels or detected by our automated systems (e.g., AbuseIPDB syncs).
- **Usernames & User IDs:** Of reported bad actors (e.g., UTTP affiliates, ban evaders).
- **OSINT & Evidence:** Screenshots, logs, URLs, and text submitted in the reporting station.

**D. Log Data**
- Command usage, error logs, and system interaction data to debug issues (like the recent cross-contamination bug) and maintain system stability.

## 3. HOW WE USE YOUR INFORMATION

- **Authentication:** To verify users and grant appropriate access to your server.
- **Threat Defense:** To globally blacklist malicious User IDs and IPs across the entire WIC network.
- **Server Security:** To track and block ban evaders and hostile actors.
- **System Maintenance:** To debug backend errors, fix authentication loops, and prevent cross-contamination.
- **Intelligence Pipeline:** To process reports and generate OSINT dossiers (as seen in the VB Reporting Station).

## 4. HOW WE SHARE INFORMATION

**A. Global Blacklist (Network-Wide Sharing)**
By using GateKeeper, you acknowledge that User IDs, IP addresses, and evidence of malicious activity reported to us are shared globally across the WIC defense network. This means a bad actor banned in Server A will be instantly flagged for Server B. 

**B. Third-Party APIs**
We may query APIs (like AbuseIPDB) to enrich our threat intelligence. We do not share your server's private configuration data with these APIs.

**C. Legal Requirements**
We will disclose information if required by law, subpoena, or to protect the safety of the community and the integrity of the WIC network. 

**We do not sell your data.** WIC is a volunteer-driven research group.

## 5. DATA SECURITY & ISOLATION
We take data security seriously. 
- **Multi-Tenant Isolation:** As part of our recent updates, all configuration data is strictly keyed by `guild_id` to prevent cross-server contamination.
- **Database Hardening:** We use fallback and validation checks to ensure that missing or empty data does not break the system or expose other servers' data.
- **Access Control:** Only authorized WIC operators have access to the backend databases.

## 6. DATA RETENTION
- **Authentication Data:** Retained for the duration of the user's membership in the server, or until the config is reset.
- **Blacklist Data:** Retained indefinitely. If a user is confirmed as a malicious actor, their ID and associated evidence are kept permanently in the global blacklist to ensure community safety.
- **Logs:** Rotated and cleared periodically to maintain system performance.

## 7. YOUR RIGHTS
- **Appeal:** If you believe you were falsely blacklisted, you can appeal in the official WIC Support Server.
- **Data Removal:** You can request the deletion of your auth data by removing the Bot from your server and contacting support. *However, blacklist data of confirmed malicious actors cannot be removed.*

## 8. CHILDREN'S PRIVACY
GateKeeper is not intended for use by individuals under the age of 13 (or the minimum age of digital consent in your country). We do not knowingly collect data from children. If we become aware of such data, we will delete it.

## 9. CHANGES TO THIS POLICY
We may update this Privacy Policy as the system evolves. Major changes will be announced in the WIC Support Server. Continued use of the Bot constitutes acceptance of the updated policy.

## 10. CONTACT
For privacy concerns, blacklist appeals, or to request StyxNet token access:
🔗 https://discord.gg/tu5CynxjZq

---
**WinterGate Intelligence Collective**
*J1L — Justice, Intelligence, Love.*
*The First Truth serves no master.*
