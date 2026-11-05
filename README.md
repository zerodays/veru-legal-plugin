# Veru Legal

Legal AI built the way legal work actually happens. Veru brings Slovenian, EU and international legislation and case law into Claude, so you can research, reason and draft with sources you can verify.

Veru is built by practising lawyers and engineers in Ljubljana and is used by Slovenian law firms, in-house legal teams and the University of Ljubljana.

## What this plugin does

This plugin connects Claude (chat, Cowork and Claude Code) to Veru's legal research through the Veru MCP server. With it, Claude can:

- **Research the law in context.** Veru pulls in the current legislation and case law relevant to your question, instead of you searching databases before every task.
- **Work from trusted official sources.** Slovenian and EU law comes from PisRS, sodnapraksa.si and EUR-Lex, with coverage of 200+ jurisdictions.
- **Read the full text.** Veru reads promising documents in full and returns the relevant statutes and decisions verbatim, not summaries.
- **Cite every source.** Statutes come with their canonical identifier (for example "ZDR-1, 115. člen" or a CELEX number) and decisions with court, case number and date, so you can stand behind what you deliver.

## Example prompts

- "Using Veru, what is the limitation period for a claim for damages under the Slovenian Obligations Code, and is there Supreme Court case law on when it starts to run?"
- "Find recent sodnapraksa.si decisions on termination of an employment contract for business reasons and summarise the key holdings."
- "Check this NDA against Slovenian and EU law and list the clauses that need revising, with the legal basis for each."
- "Which GDPR provisions and Slovenian ZVOP-2 articles apply to processing employee biometric data? Cite the sources."

## Requirements

- A Veru account on a paid plan. Every plan includes the Veru Claude Connector / MCP. See pricing at [veru.legal](https://veru.legal/en/pricing).
- Sign in with your Veru account when Claude asks you to connect the Veru server.

Setup assistance is included with the Prime plan. Contact us and we will help you get connected.

## What the plugin sends and where

This plugin adds one remote MCP server, `veru`, at `https://veru.legal/mcp`. It does not run any local code, hooks or scripts.

When Claude calls the Veru tool, it sends the research questions and the context Claude writes for that call, which can include excerpts from your conversation or documents, to Veru's servers. Veru searches official legal sources and returns the relevant legislation and case law. The tool only reads: it does not change anything in your Veru account. Veru:

- hosts documents within the EU,
- does not train AI models on your data,
- uses zero data retention with its AI model providers.

See the [Veru privacy policy](https://veru.legal/en/privacy) and [terms](https://veru.legal/en/terms) for details.

## Important

Veru is a tool for legal professionals and does not replace professional legal judgment. Always review the cited sources and the final work product before relying on it.

## Support

- Website: [veru.legal](https://veru.legal)
- Email: contact@veru.legal

verulabs d.o.o., Miklošičeva cesta 30, 1000 Ljubljana, Slovenia, EU
