# Veru Legal

Legal AI built the way legal work actually happens. Veru brings Slovenian and EU legislation, case law and your matter documents into Claude, so you can research, reason and draft with sources you can verify.

Veru is built by practising lawyers and engineers in Ljubljana and is used by Slovenian law firms, in-house legal teams and the University of Ljubljana.

## What this plugin does

This plugin connects Claude (chat, Cowork and Claude Code) to your Veru workspace through the Veru MCP server. With it, Claude can:

- **Research the law in context.** Veru automatically pulls in the current legislation and case law relevant to your question, instead of you searching databases before every task.
- **Work from trusted official sources.** Slovenian and EU law comes from PisRS, sodnapraksa.si and EUR-Lex, with coverage of 200+ jurisdictions.
- **Reason like a trained lawyer.** Veru handles overlapping rules, conflicts of law and methodological questions, not just "what does the statute say".
- **Show its work.** Every conclusion is traceable: the reasoning steps are visible and every source is cited, so you can stand behind what you deliver.
- **Stay organised by matter.** Each matter in Veru has its own workspace with its own documents and context, kept separate from your other matters, just like your case files.
- **Run work in parallel.** Use concurrent Veru agents across several matters or questions at once.

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

When Claude calls a Veru tool, it sends your request and any matter content Claude includes in that call to Veru's servers to retrieve legislation, case law and matter documents and to return results. Veru:

- hosts documents within the EU,
- does not train AI models on your data,
- uses zero data retention with its AI model providers.

See the [Veru privacy policy](https://veru.legal/en/privacy) and [terms](https://veru.legal/en/terms) for details.

## Important

Veru is a tool for legal professionals and does not replace professional legal judgment. Always review the cited sources and the final work product before relying on it.

## Support

- Website: [veru.legal](https://veru.legal)
- Email: anze@veru.legal
- Support in Slovenia, by email, by phone and in person

verulabs d.o.o., Miklošičeva cesta 30, 1000 Ljubljana, Slovenia, EU
