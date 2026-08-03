# Privacy Policy for AdamC Bot

**Effective Date:** August 3, 2026  
**Last Updated:** August 3, 2026  

This Privacy Policy explains how **AdamC Bot** ("we", "us", or "our") collects, processes, uses, stores, and protects data when you invite or interact with the Bot within a Discord guild (server). We are committed to maintaining the privacy and security of all user and server data in accordance with Discord Developer Policies and applicable data protection regulations.

---

## 1. Information We Collect & Process

To deliver core automated moderation, member management, and utility features, AdamC Bot processes the following limited categories of data:

### A. Discord Guild & Channel Identifiers (Stored)
- **Guild IDs & Channel IDs:** Unique numerical identifiers assigned by Discord used exclusively to save server configurations, auto-mod preferences, custom prefixes, and logging channel settings.
- **Role IDs:** Role identifiers used for automated role assignment (Auto-Role) and permission checks.

### B. User Identifiers (Processed / Ephemeral)
- **User IDs & Usernames:** Numerical identifiers used to execute moderation logs, process member profiles via commands like `!userinfo`, and track server join/leave events.
- **Account Join Dates:** Retrieved temporarily when executing member informational utilities.

### C. Message Content (Real-Time Ephemeral Processing ONLY)
- **Real-Time Text Processing:** The Bot reads message content in volatile RAM **strictly in real-time** to perform automated moderation checks (filtering prohibited links, profanity, and invite spam) and to parse prefix commands (e.g., `!say`, `!warn`).
- **NO Storage of Message Content:** **Message content is NEVER stored, saved, written to disk, logged, or recorded in any persistent database.** Once a message is processed for moderation or command execution, it is immediately discarded from memory.

---

## 2. How We Use Collected Data

We strictly use processed and stored data for the following explicit operational purposes:
1. **Core Functionality:** Executing auto-moderation filters, welcome/leave notifications, auto-roles, and administrative commands.
2. **Server Configuration:** Storing custom server preferences set by authorized server administrators.
3. **Security & Anti-Abuse:** Preventing bot abuse, rate-limit violations, and malicious spam within guilds.

---

## 3. Data Protection, Storage & Security Measures

- **No Sale or Third-Party Sharing:** We **NEVER** sell, rent, trade, or share any user or guild data with third-party advertisers, analytics brokers, or external entities.
- **Secure Infrastructure:** Saved configuration data (Guild IDs and settings) is stored in a secure, password-protected database environment with restricted access limited exclusively to the lead developer.
- **Encryption:** All communications between AdamC Bot, Discord APIs, and database endpoints occur over encrypted connections (HTTPS/WSS).

---

## 4. Data Retention & Erasure Rights

- **Data Retention:** Server configuration data is retained only for as long as AdamC Bot remains in the respective server.
- **Automatic Cleanup:** When AdamC Bot is removed (kicked or banned) from a Discord server, associated guild configurations can be purged.
- **Right to Erasure (Data Deletion):** Server owners and users have the right to request full removal of any stored configuration data linked to their Guild ID or User ID by contacting us directly through our official Discord support channel.

---

## 5. Compliance with Discord Policies
AdamC Bot operates in strict compliance with Discord’s [Developer Terms of Service](https://discord.com/developers/docs/policies-and-agreements/developer-terms-of-service) and [Developer Policy](https://discord.com/developers/docs/policies-and-agreements/developer-policy).

---

## 6. Updates to This Privacy Policy
We may update this Privacy Policy periodically to reflect feature additions or technical changes. Any revisions will be published here with an updated revision date.

---

## 7. Contact Information
For privacy inquiries, data deletion requests, or technical support, please contact the bot developer via our official Discord support server or direct contact.
