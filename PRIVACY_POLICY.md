# Privacy Policy — Izumi Botnata

Last updated and effective: September 6, 2026

## 1. Scope and operator

[Dirty-Octopus](https://github.com/Dirty-Octopus) operates Izumi Botnata (the “Bot”), a personal Discord assistant deployed with OpenClaw to control the operator’s own computer. The Bot is intended for the operator alone and is not offered to other users. This Policy covers the operator’s deployment; it does not replace Discord’s or a model provider’s own privacy terms.

Contact: [policy repository Issues](https://github.com/Dirty-Octopus/TOS-and-PP-4-discord-bot/issues). This is a public contact channel. Post only a minimal request to contact the operator; do not post private messages, identifiers you do not want public, credentials, or files. If necessary, the operator will arrange a private channel before requesting details.

## 2. Information processed

The information processed depends on the requested task and enabled permissions:

- **Discord account and routing data:** user and message IDs, display names, server/channel/thread IDs, timestamps, and authorization information needed to receive commands and send replies.
- **Conversation content:** prompts, commands, relevant message context, attachments supplied for a task, and generated replies.
- **Computer-tool data:** commands, file content, paths, application information, screenshots, and tool results when an enabled tool accesses them to complete a task. This does not mean every tool is enabled or that all computer data is collected.
- **Local assistant records:** OpenClaw may persist conversations, summaries, memory notes, task artifacts, configuration, and diagnostic logs on the deployment computer. The operator has administrative access to those records.

The deployment is intended to restrict access to the operator and avoid processing other people’s conversations. Discord permissions and OpenClaw access controls must enforce that restriction; this document itself does not enforce it. Do not submit secrets or sensitive personal data through the Bot.

## 3. Purposes

Information is used to respond to the operator, perform authorized computer tasks, retain useful context and memory, troubleshoot errors, prevent unauthorized access, and address privacy requests. The operator does not sell Discord API data, use it for advertising, or disclose it to data brokers.

The operator does not use Discord message content to train or fine-tune AI models. Supplying context for a model response is distinct from training. Any external model service must be used under terms and settings consistent with Discord’s restrictions on training with API message content.

## 4. Where information goes

**Discord.** Discord delivers messages and Bot responses and processes data under the [Discord Privacy Policy](https://discord.com/privacy). Anyone with access to a channel where the Bot responds may be able to see those responses.

**Local OpenClaw deployment.** The operator’s computer processes tool actions and may store the assistant records described above. Self-hosting OpenClaw does not mean that all model processing stays on that computer.

**Claude/model services.** Claude is the intended model family. When an external model is used, prompts, relevant conversation context, and necessary tool results or attachments may be transmitted to the configured model endpoint to generate responses. Computer content included in that context may therefore leave the computer. For direct Anthropic services, see the [Anthropic Privacy Policy](https://www.anthropic.com/legal/privacy). Provider retention and any additional account-specific terms depend on the actual service and settings; this Policy does not promise zero provider retention. A Claude model name alone does not establish that the endpoint is operated directly by Anthropic. If a separate gateway, reseller, or other provider is selected, the operator must identify it and its policy here before sending Discord data through it.

**Other tools and services.** A task that uses a connected external service may send that service the task data needed to carry it out. No additional integration is identified for this initial deployment. The operator must update this Policy to identify any such recipient and its purpose before enabling it to receive Discord data.

External providers may process data outside the operator’s country. The operator must check the selected service’s processing locations and any legally required safeguards before transferring personal information. Information may also be disclosed where legally required or at the affected person’s express direction, subject to Discord’s requirements.

## 5. Retention and deletion

This personal deployment does not promise an automatic fixed-day purge. Local conversation records, memory, and task files may persist between sessions until the operator removes them. They are retained only while necessary for the described assistant functionality. Diagnostic records are retained only as needed for troubleshooting or security.

The operator will promptly delete Discord API data when it is no longer needed, when the affected person or Discord requests deletion, or when the Bot is permanently discontinued, except for any narrowly scoped retention required by law. This applies to relevant transcripts, summaries, memory notes, logs, task artifacts, and operator-controlled backup or archive copies. Applicable service-provider deletion requests must also be made where required.

Resetting a conversation, deleting a Discord message, or removing the Bot may not erase local copies or derived memory. Provider-held copies follow the applicable provider’s retention and deletion terms. Discord-held copies are handled by Discord under its own policy.

## 6. Requests and unintended collection

The operator can stop the Bot, revoke permissions, and remove stored records directly. If someone else believes the Bot processed their information inadvertently, they may request access, correction, or deletion through the contact in Section 1. Do not post the underlying data publicly.

The operator may request proportionate verification through an arranged private channel and will respond promptly within applicable legal deadlines. Requests can cover stored content and derived summaries or memory. Any legally required retention or other lawful limit will be explained. Unintentionally received data that is not needed for the service will be removed.

Depending on applicable law, affected people may also have rights to portability, restriction, objection, withdrawal of consent where relevant, and complaints to a data protection authority. This Policy does not assume that personal use removes every legal obligation.

## 7. Security and age limits

The operator is responsible for maintaining operator-only access, protecting Bot and model credentials, encrypting stored Discord API data, and securing communications to providers as required by Discord’s developer terms. These are operational requirements, not a claim that the deployment has undergone a security audit. Unauthorized access must be addressed promptly, with notices to Discord and affected people as required.

The Bot is not intended for children below Discord’s minimum age or a higher applicable local minimum. If such a child’s data is received inadvertently, the operator will stop that processing and promptly remove it as required.

## 8. Changes

This Policy will be updated when the Bot’s providers, integrations, purposes, or audience change. Before permitting other users, the operator must establish appropriate user-facing disclosures and controls. Material changes will be communicated to affected users where required, and any legally required consent will be obtained separately.
