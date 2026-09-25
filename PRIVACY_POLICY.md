# Privacy Policy — SynthX Development

**Effective Date:** March 26, 2026  
**Last Updated:** September 25, 2026  
**Governing Entity:** SynthX Development ("SynthX", "we", "us", "our")  
**Contact / Data Protection Officer:** `suhansalian740@gmail.com`  
**Support Server:** [https://discord.gg/WKX5HHPmWz](https://discord.gg/WKX5HHPmWz)

---

## 1. Introduction & Overview
SynthX Development is dedicated to protecting user privacy and maintaining transparency regarding how personal and server data is collected, stored, and processed. This Privacy Policy details our data governance practices for the **SynthX Discord Application** and related web services in compliance with Discord's Developer Policy, the General Data Protection Regulation (GDPR), the California Consumer Privacy Act (CCPA), and the Children's Online Privacy Protection Act (COPPA).

---

## 2. Roles: Data Controller vs. Data Processor
Under global data privacy laws:
1. **Discord Server Owners as Data Controllers:** When a server administrator configures SynthX to log messages, track moderation actions, or monitor joins/leaves, the server owner is the primary **Data Controller** determining the purpose and means of processing server-specific data.
2. **SynthX as Data Processor:** SynthX functions as a **Data Processor**, acting solely upon the technical configuration and automated events triggered within Discord guilds.

---

## 3. Categories of Data Collected

### A. User Information (Individual Accounts)
- **Discord User IDs (Snowflake IDs):** Unique numeric identifiers provided by Discord used to attribute moderation cases, leveling statistics, AFK states, custom role ownership, warnings, and permission hierarchies.
- **Usernames, Discriminators & Avatars:** Retrieved dynamically via the Discord API in real-time to render visual items (e.g., leveling cards, profile cards, welcome banners). These are **not** permanently cached or stored in secondary databases.
- **Message Content:**
  - *Automod & Spam Mitigation:* Processed ephemerally in volatile memory (RAM) to detect spam, invite links, caps, and malicious phrases. Discarded immediately after processing unless logged to a server's configured audit channel.
  - *AI Chatbot Conversations:* When explicitly invoked, user prompts and temporary context (up to the configured history limit) are processed to formulate contextual responses.
- **Command Interactions:** Timestamped logs of slash commands and prefix executions to monitor system health and prevent exploitation.

### B. Server (Guild) Information
- **Guild IDs:** Used to isolate server-specific settings and databases.
- **Channel IDs & Role IDs:** Stored to maintain configurations (e.g., ticket panels, logging channels, autoroles, whitelists, AntiNuke rules).
- **Audit & Incident Records:** Timestamps, executor IDs, and action types for bans, kicks, timeouts, and AntiNuke security events.
- **Invite Tracking Data:** Stored invite codes and usage counters to track invite origins if enabled.

---

## 4. Legal Basis for Processing (GDPR Article 6)
We process personal data only when a recognized legal basis exists:
1. **Contractual Performance:** To deliver the automated services requested when the bot is invited or commanded.
2. **Legitimate Interests:** To protect Discord communities from malicious raids, nukes, and unauthorized administrative actions via AntiNuke and Sentinel modules.
3. **Legal Compliance:** To enforce our Terms of Service and adhere to Discord Developer Terms.

---

## 5. Data Storage, Security & Retention

1. **Storage Infrastructure:** Data is stored in secure SQLite database instances utilizing Write-Ahead Logging (WAL) and hosted in restricted-access server environments.
2. **Data Minimization:** We only collect and retain the minimum amount of data required to perform core functionality.
3. **Retention Periods:**
   - **Configuration Data:** Retained for the duration of the bot's presence in a server.
   - **Moderation Case Logs:** Retained until cleared by server administrators or upon formal data deletion request.
   - **Volatile Cache / Voice Sessions:** Purged immediately upon session termination.
   - **Ticket Transcripts:** Stored in accordance with individual guild settings or purged after 30 days.

---

## 6. Automated Decision-Making & Security Profiling
SynthX features automated security algorithms (AntiNuke and Sentinel):
1. **Sliding-Window Action Tracking:** If an account executes a high volume of dangerous administrative actions (e.g., mass channel deletions, mass kicks) in a few seconds, the bot automatically triggers mitigating actions (e.g., role-strip or quarantine).
2. **Anti-Raid Heuristics:** New member accounts exhibiting known botnet or raid signatures may be temporarily quarantined or flagged for verification.
3. **Human Review:** All automated moderation decisions can be audited, modified, or reversed by server owners and administrators.

---

## 7. Third-Party Sub-processors & External Services
To provide specific functionality, SynthX may transmit data to trusted third-party providers:
- **Discord Inc. (Gateway & API):** All bot interactions operate over the Discord platform. Discord's privacy practices are governed by the [Discord Privacy Policy](https://discord.com/privacy).
- **OpenAI LLC:** Utilized for AI conversational responses. Prompts transmitted are subject to [OpenAI Privacy Policy](https://openai.com/policies/privacy-policy) and data processing terms.
- **Prodia Inc.:** Utilized for AI image generation when requested by users.

SynthX **NEVER** sells, monetizes, rents, or discloses personal user data to third-party data brokers, marketers, or advertisers.

---

## 8. User Rights (GDPR & CCPA Rights)
Depending on your geographic location, you possess explicit legal rights regarding your personal data:
1. **Right of Access (Article 15 GDPR):** You may request a summary of the personal data associated with your Discord User ID.
2. **Right to Rectification (Article 16 GDPR):** You may request correction of inaccurate data.
3. **Right to Erasure ("Right to be Forgotten" - Article 17 GDPR / CCPA):** You may request the permanent deletion of your data from our databases.
4. **Right to Restrict Processing:** You may request that we suspend processing your data.

### How to Exercise Your Rights:
To submit a data access or deletion request:
- Join our official support server: [https://discord.gg/WKX5HHPmWz](https://discord.gg/WKX5HHPmWz) and open a privacy ticket.
- Or email our Data Protection contact directly at `suhansalian740@gmail.com` with your Discord User ID and proof of account ownership. Requests are processed within thirty (30) days without charge.

---

## 9. Protection of Minors (COPPA Compliance)
SynthX does not knowingly solicit or collect data from children under the age of 13. If we become aware that personal information has been collected from a user under 13 without verified parental consent, we will take immediate steps to purge such data from our records.

---

## 10. Security & Breach Notification
We implement modern technical safeguards to defend stored data against unauthorized access, loss, or alteration. In the unlikely event of a security breach compromising user data, we will notify affected server owners and comply with applicable statutory notification timelines.

---

## 11. Policy Amendments
We reserve the right to revise this Privacy Policy periodically. Any modifications will be indicated by the "Last Updated" timestamp at the top. We encourage users and administrators to review this policy periodically.

---

## 12. Contact Information
For privacy questions, legal notices, or data subject inquiries:
- **Data Controller/DPO:** sae (`saecodess`)
- **Email:** `suhansalian740@gmail.com`
- **Support Community:** [https://discord.gg/WKX5HHPmWz](https://discord.gg/WKX5HHPmWz)
