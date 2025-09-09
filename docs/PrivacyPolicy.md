# Privacy Policy — Post A Note Bot

**Effective Date:** November 8, 2024
**Bot Name:** Post A Note
**Owner / Controller:** FiveO Development | Officer Mills
**Documentation (TOS & Privacy Policy):** [https://fiveo-development.gitbook.io/docs/postanote-guide/](https://fiveo-development.gitbook.io/docs/postanote-guide/)

---

## 1. What this bot does

Post A Note is a Discord bot whose purpose is to let users create and pin **posted notes** in servers. The bot primarily uses Slash commands but retains a single legacy prefix command: **`?stick`**.

This command exists because it allows users to include multi-line spacing and paragraph breaks with Discord markdown — functionality that slash commands alone cannot fully support in some Discord clients.

When you use `?stick` or `/stick`:

* The bot reads the message content you provide in order to properly format and post your note.
* The note is then posted back to Discord as a message.

---

## 2. Data we collect and why

**A. Message Content**

* **Collected when:** You use the legacy prefix command `?stick` or the `/stick` slash command.
* **Purpose:** To preserve markdown formatting, line spacing, and paragraphs in your posted note.
* **Storage:** Not stored outside the application. Once processed and posted, message content is only retained by Discord as part of the server’s chat history.

**B. Discord Identifiers**

* Includes: User ID, guild (server) ID, channel ID, message ID, and timestamps.
* **Purpose:** To determine where to post notes, validate permissions, and provide troubleshooting support.

**C. Diagnostic Logs (Minimal)**

* May include: Command usage events, error traces, and timestamps.
* **Purpose:** Debugging, performance monitoring, and abuse prevention.
* **Retention:** Up to **30 days**. Logs do not include full message content.

**D. Sensitive Data**

* The bot does **not** request payment data or intentionally collect sensitive personal information. If you type sensitive data into a posted note, it will be visible publicly in your server.

---

## 3. How we use data

* To process your note request and post it correctly.
* To validate permissions and ensure the bot functions in your server.
* To debug, monitor performance, and prevent abuse.

**We do not:**

* Sell or share your data with advertisers.
* Store message content outside the bot.
* Use your content for AI training or profiling.

---

## 4. Storage & retention

* **Message content:** Only held temporarily in memory to process the `?stick` command. Once posted, no external storage occurs.
* **Logs:** Minimal, non-content logs retained up to **30 days** for debugging and abuse prevention.
* **Identifiers/metadata:** Only retained temporarily for operations and logs as described above.

---

## 5. Third parties and sharing

* **Discord:** Posted notes are sent via Discord, and message storage is handled by Discord’s platform.
* **Hosting provider:** The bot is hosted on secure third-party infrastructure. Runtime data and minimal logs may pass through hosting systems as needed for operations.
* **Legal:** Data may be disclosed if required to comply with applicable laws or valid legal requests.
* **No advertising or marketing:** Your data is never shared with advertisers.

---

## 6. Security

We follow industry-standard security practices:

* Bot tokens and secrets stored in environment variables, never in code.
* Access to systems and logs restricted to authorized administrators.
* Minimal permission usage in Discord servers (only what is needed to function).

---

## 7. Your rights & choices

* **Delete a posted note:** You or your server admins can delete notes directly from Discord.
* **Remove the bot:** Removing the bot from your server stops all data processing.
* **Disable legacy command:** Server admins can request disabling of `?stick` if they want to restrict bot access to message content.

---

## 8. Children

The bot is not intended for children under 13 or the minimum age of digital consent in your jurisdiction. We do not knowingly collect data from children.

---

## 9. Changes to this policy

This Privacy Policy may be updated periodically. Updates will be posted at:
[https://fiveo-development.gitbook.io/docs/postanote-guide/](https://fiveo-development.gitbook.io/docs/postanote-guide/)

---

## 10. Contact

For questions, concerns, or requests regarding this policy, please refer to our documentation:
[https://fiveo-development.gitbook.io/docs/postanote-guide/](https://fiveo-development.gitbook.io/docs/postanote-guide/)
## 12. Short copy for Discord Developer application

> Post A Note requests Message Content Intent solely to read user messages when the legacy `?stick` command is used so the bot can preserve multi-line spacing and Markdown formatting. We **do not store message content outside the bot application** and do not use content for advertising or training. Full Privacy Policy: [https://fiveo-development.gitbook.io/docs/postanote-guide/](https://fiveo-development.gitbook.io/docs/postanote-guide/)
