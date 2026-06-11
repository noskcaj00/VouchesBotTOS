# Privacy Policy — VouchesCounter

Effective date: 2026-06-10

This Privacy Policy describes how the VouchesCounter Discord bot ("the Service","we" or "us") collects, uses, and stores information when it runs on a Discord server. This policy applies only to data handled by the Service and does not cover Discord’s own data practices. If you are a server owner or administrator, you are responsible for ensuring your server members are informed about any data processing performed by the bot.

## 1. Data Controller
The project owner / maintainer of the VouchesCounter repository is the data controller for personal data processed by this Service. Contact information is available in the project repository documentation.

## 2. What Data We Collect
- Messages: When you request a vouches count, the Service scans the message history of the configured channel (`#🤝│vouches`) to detect message mentions. The bot reads message metadata and mentions to compute counts.
- User identifiers: The Service may process Discord user IDs, usernames, display names, and discriminators in order to resolve and report counts.
- Logs: Operational logs (including timestamps, server and channel identifiers, and command inputs) may be recorded for debugging and support.

The Service does not collect message contents for purposes beyond counting mentions unless explicitly configured in custom deployments.

## 3. How We Use Data
- To provide the core function: counting mentions for the requested user in the configured channel.
- To resolve users and channels for command inputs.
- To diagnose, debug, and improve the Service via operational logs.

## 4. Legal Basis
If you are in a jurisdiction that requires a legal basis for processing (e.g., GDPR), the Service processes data on the basis of legitimate interests (providing the bot functionality) and performing the request initiated by a user or server administrator.

## 5. Data Retention
- The Service only accesses message history on demand when a count is requested. By default, it does not persist message contents long-term. Operational logs may be retained for a limited period to assist with debugging; retention duration depends on the deployment and platform used.
- If you self-host or deploy the bot, you control retention policy and any persistent storage.

## 6. Third-Party Services
If you deploy the Service to a hosting provider (e.g., Fly.io, Replit, Render), those providers may have their own data handling and retention practices. You should consult the provider’s privacy policies and configure secrets and logging accordingly.

## 7. Security
We recommend following best practices:
- Keep your bot token secret and store it in environment variables or the host platform's secret store.
- Grant the bot only the permissions it needs (View Channel, Read Message History, Send Messages).
- Use secure hosting and enable access controls on the deployment platform.

## 8. Your Rights
Depending on your jurisdiction, you may have rights such as access, rectification, deletion, restriction of processing, and objection. To exercise these rights, contact the project owner via the repository contact method. Note that in public Discord servers, message contents are controlled by Discord and the server owner; the bot can only act on data available to it.

## 9. Children
The Service is not directed to children under the applicable minimum age. If you are a parent or guardian and become aware that your child provided personal information to the Service, contact the project owner to request deletion of the data where applicable.

## 10. Changes to this Policy
We may update this Privacy Policy from time to time. Any changes will be posted in the project repository with an updated effective date.

## 11. Contact
For questions about privacy or data handling, contact the project owner via the repository's contact channel.

---
This Privacy Policy is a general template and does not constitute legal advice. For legally binding, jurisdiction-specific privacy documentation, consult a qualified legal professional.
