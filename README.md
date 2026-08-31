# Awesome Grok Bots

<p align="center">
  <a href="https://dashboard.composio.dev/signup?utm_source=github&amp;utm_medium=readme&amp;utm_campaign=awesome-grok-bots">
    <img src="cover_image.png" alt="Awesome Grok Bots — serious AI teammates for knowledge work">
  </a>
</p>

A curated collection of Grok Bot blueprints and verified public templates for serious knowledge work.

The repository focuses on product judgment, engineering leadership, research, analysis, reliability, and governance. It deliberately excludes novelty assistants, personality prompts, shopping helpers, and vague “do everything” agents.

## What a Grok Bot is

Grok Bot is an agent product for handing real work to persistent, named AI teammates. A Bot has its own conversation and durable context, can use a browser, filesystem, terminal, connectors, and MCP tools on a cloud computer, and can keep working after your laptop closes.

Bots can coordinate with one another and turn a repeatable process into a skill or scheduled routine. All Bots on an account share the same user-scoped cloud computer, files, browser sessions, and app logins; separate Bots are not security boundaries.

A public `x.ai/bot/...` link copies a creator's Bot configuration into another account. It does not copy the creator's conversations, computer, files, or logins. See the official [overview](https://docs.x.ai/grok-bot/overview), [Bot documentation](https://docs.x.ai/grok-bot/bots), and [security guidance](https://docs.x.ai/grok-bot/approvals-security-and-privacy).

## How to install a Bot from this repository

Entries in the directory use one of two formats:

### Install a public share

1. Open the listed `x.ai/bot/...` link.
2. Review the Bot's description and shared context.
3. Click **Add to Grok Bot**. Grok Bot creates a copy in your account.
4. Review its memories, skills, routines, and approval boundaries before connecting any apps.
5. Customize it for your organization and run the first few tasks under supervision.

### Install a copy-paste prompt

1. Open the linked file under [`templates/`](templates/).
2. In Grok Bot, create a new Bot and give it the name shown in the template.
3. Copy the entire Markdown brief into the Bot's conversation and ask it to adopt the instructions as its operating context.
4. Answer its setup questions and replace any bracketed placeholders with your systems, owners, vocabulary, and risk thresholds.
5. Connect only the apps required for its job, then test it on a bounded task before adding routines or granting broader access.

The Markdown files are readable setup briefs, not one-click installers. A true install button requires a public Grok-hosted `x.ai/bot/...` share link.

## Bots

This list mixes two clearly labeled formats:

- **Copy-paste prompt** — an original Markdown setup brief hosted in this repository.
- **Public share** — a creator's installable `x.ai/bot/...` configuration, with creator attribution or a source post on X.

The Markdown files have no special meaning to Grok. Create a Bot in the app, paste the brief into its setup conversation, and adapt the connections, owners, and routines to your organization.

### Product and decisions

- **Copy-paste prompt** — [**Product Lead**](templates/product-lead.md) maintains product context, turns evidence into scoped bets, and delegates bounded work without losing release judgment.
- **Public share** — [**Product Lead**](https://x.ai/bot/KHEDSnSW1R74FH9kmghlA) turns evidence into scoped bets and linked decision memos using the tested Product Decision Review skill. Created and tested for this repository.
- **Public share** — [**Mercury — Product Lead**](https://x.ai/bot/lk1yHfim5Ayra0Q0QlN3L) retains system understanding and release judgment while delegating narrow implementation. By [@chiefjeeb](https://x.com/chiefjeeb). [Source](https://x.com/chiefjeeb/status/2094223658151502326)
- **Copy-paste prompt** — [**Customer Evidence Synthesizer**](templates/customer-evidence-synthesizer.md) converts interviews, tickets, calls, and usage signals into traceable problem themes.
- **Copy-paste prompt** — [**Competitive Intelligence Analyst**](templates/competitive-intelligence-analyst.md) maintains an evidence-backed competitor change log and decision-relevant briefs.
- **Public share** — [**Competitor Watching**](https://x.ai/bot/5PKSzU0ruN_DQbNXc7m0N) compares pricing, releases, features, hiring, and messaging across a defined competitor set, then alerts only on material changes. By [@scheemunai](https://x.com/scheemunai).
- **Copy-paste prompt** — [**Experiment Reviewer**](templates/experiment-reviewer.md) checks hypotheses, instrumentation, statistical claims, and ship/iterate/stop decisions.
- **Copy-paste prompt** — [**Decision Memory**](templates/decision-memory.md) preserves decisions, alternatives, assumptions, owners, and revisit triggers.
- **Public share** — [**Lennybot**](https://x.ai/bot/VjbtJ_qTdzbhJGmXdvTIc) answers product and growth questions against Lenny's published archive rather than the open web. By [@lennysan](https://x.com/lennysan). [Source](https://x.com/lennysan/status/2093428147194847238)

### Engineering and reliability

- **Public share** — [**Loops**](https://x.ai/bot/Ub3T7usX-c6yRQibQq83P) gathers repository context, writes a testable goal, launches coding agents, reviews their work, and merges after verification. By [@mattyp](https://x.com/mattyp). [Source](https://x.com/mattyp/status/2093380201128595966)
- **Public share** — [**1000x Product Engineer**](https://x.ai/bot/sQDD87Gp6VLT0m99tFpzu) ships Convex, TanStack, and React web products with an emphasis on simple UI. By [@TomZarebczan](https://x.com/TomZarebczan).
- **Public share** — [**Agent Looper**](https://x.ai/bot/AETdGbRRNWfckrRGv22LD) keeps a local coding agent iterating until a user-defined acceptance check passes. By [@dancingteeth](https://x.com/dancingteeth).
- **Copy-paste prompt** — [**Engineering Program Lead**](templates/engineering-program-lead.md) converts a goal into parallel workstreams, verifies handoffs, and keeps one source of execution truth.
- **Public share** — [**Projects Manager**](https://x.ai/bot/FU-Ev6_Ju4lFGWwWRD0GD) coordinates specialist coder, designer, researcher, and writer Bots against Notion project rows. By [@ericzakariasson](https://x.com/ericzakariasson). [Source](https://x.com/ericzakariasson/status/2093381689041109349)
- **Copy-paste prompt** — [**Technical RFC Reviewer**](templates/technical-rfc-reviewer.md) reviews architecture proposals for assumptions, failure modes, migration risk, and observability.
- **Public share** — [**PR Reviewer**](https://x.ai/bot/rt629UEZFtE4Wz0A_0c37) reviews pull requests risk-first, looking for missing tests, thin context, and mismatches between the promise and the diff. By [@mustafaergisi](https://x.com/mustafaergisi).
- **Copy-paste prompt** — [**Incident Commander**](templates/incident-commander.md) maintains the incident timeline, hypotheses, ownership, and stakeholder updates while humans control production.
- **Public share** — [**Examiner**](https://x.ai/bot/rBnJhXhks-_7n1zhZCN3E) keeps a factual change timeline so failures can be correlated with recent product, configuration, permission, and process changes. By [@liam_fallen](https://x.com/liam_fallen). [Source](https://x.com/liam_fallen/status/2093382730352304381)
- **Copy-paste prompt** — [**Release Readiness Reviewer**](templates/release-readiness-reviewer.md) builds an evidence-based go/no-go packet across tests, rollout, rollback, monitoring, and support.
- **Copy-paste prompt** — [**Security Triage Analyst**](templates/security-triage-analyst.md) normalizes security findings, gathers evidence, proposes severity, and routes remediation without changing systems.
- **Public share** — [**Speed Lab**](https://x.ai/bot/LEbVr_WZ-cym7XwIm7xf5) runs a measured research-and-improvement loop on website rendering performance. By [@pwnies](https://x.com/pwnies).

### Research and analysis

- **Copy-paste prompt** — [**Literature Reviewer**](templates/literature-reviewer.md) produces reproducible literature maps with search strategy, evidence tables, and uncertainty.
- **Copy-paste prompt** — [**Research Brief Writer**](templates/research-brief-writer.md) answers a decision question with source-ranked evidence, counterevidence, and explicit unknowns.
- **Public share** — [**Ethan**](https://x.ai/bot/F5Mm-0O3fPPZjYGIdsycE) runs a multi-skill research desk that checks its own findings before reporting. By [@jumperz](https://x.com/jumperz).
- **Public share** — [**Thoth**](https://x.ai/bot/W4Z5pvEm6UgCml48Ig4dT) produces research dossiers and maintains a searchable filing system for the resulting knowledge. By [@RichSilver](https://x.com/RichSilver).
- **Public share** — [**Frontier Model Watch**](https://x.ai/bot/YHqn0iTQuvI-8LC01IP6S) monitors official releases from major AI labs and issues a short, source-focused digest only when something changed. By [@GuleidAmina](https://x.com/GuleidAmina).
- **Copy-paste prompt** — [**Due Diligence Analyst**](templates/due-diligence-analyst.md) builds claim ledgers and risk-focused diligence memos from primary materials.
- **Copy-paste prompt** — [**Data Quality Investigator**](templates/data-quality-investigator.md) traces anomalous metrics through lineage, definitions, freshness, and transformation checks.
- **Public share** — [**Data Science (Querie)**](https://x.ai/bot/Bu2sEQqu0hEjpbzN_07D3) owns analytics queries, spreadsheet pulls, and metric-definition work. By [@egavrilenko11](https://x.com/egavrilenko11).
- **Public share** — [**Interrogator**](https://x.ai/bot/-TlSH1rNkA-c2JLsFFVc7) maintains an assumption register and checks whether material beliefs are still supported by current evidence. By [@liam_fallen](https://x.com/liam_fallen). [Source](https://x.com/liam_fallen/status/2093382730352304381)
- **Public share** — [**Sherlock Holmes**](https://x.ai/bot/fXHgGtuPfTcHBTVKSCZ1d) investigates unexplained changes by separating facts, suspects, eliminated causes, likely explanations, and next tests. By [@liam_fallen](https://x.com/liam_fallen). [Source](https://x.com/liam_fallen/status/2093382730352304381)
- **Copy-paste prompt** — [**Financial Variance Analyst**](templates/financial-variance-analyst.md) explains plan-versus-actual variance with reconciled evidence and review-ready commentary.
- **Public share** — [**Blockchain Data Expert**](https://x.ai/bot/eyFr_G8h9UmrQHNpZpNfx) queries Graph Protocol subgraphs to track selected tokens and protocols. By [@data_nexus](https://x.com/data_nexus). [Source](https://x.com/data_nexus/status/2094265024227192946)

### Operations and governance

- **Copy-paste prompt** — [**Contract Obligation Tracker**](templates/contract-obligation-tracker.md) extracts obligations, dates, owners, dependencies, and evidence links without giving legal advice.
- **Copy-paste prompt** — [**Compliance Evidence Manager**](templates/compliance-evidence-manager.md) maps controls to current evidence, identifies gaps, and prepares reviewer-ready packets.
- **Copy-paste prompt** — [**Vendor Risk Analyst**](templates/vendor-risk-analyst.md) evaluates vendor evidence across security, privacy, resilience, concentration, and exit risk.
- **Copy-paste prompt** — [**Risk Register Manager**](templates/risk-register-manager.md) maintains decision-useful risks with evidence, movement, mitigations, owners, and escalation triggers.
- **Copy-paste prompt** — [**Executive Briefing Editor**](templates/executive-briefing-editor.md) turns operating inputs into a concise, traceable weekly decision brief.
- **Public share** — [**Harvey Specter**](https://x.ai/bot/lkkCqhC1jBFp6ouZOQd9m) researches leverage for a deal, renewal, or quote while keeping signatures and spending with the human. By [@liam_fallen](https://x.com/liam_fallen). [Source](https://x.com/liam_fallen/status/2093382733019939198)

### Bot design and safety

- **Public share** — [**Dr. Eggbot**](https://x.ai/bot/93gOz3op1UQdBdbekQFLK) interviews the user, then creates a tightly scoped Bot with one job, explicit anti-jobs, and a verification bar. By [@poteto](https://x.com/poteto). [Source](https://x.com/poteto/status/2093392701005946931)
- **Public share** — [**Alfred**](https://x.ai/bot/KZ9xav0Qad1U5QigEn7rh) designs, audits, and governs the smallest useful Bot organization. By [@heyrobinai](https://x.com/heyrobinai). [Source](https://x.com/heyrobinai/status/2093393717545648305)
- **Public share** — [**Bot Template Scanner**](https://x.ai/bot/cGcG0msqfz7o7J3QMLhbE) inspects a public template and returns a `CLEAN`, `WARN`, or `BLOCK` security assessment before installation. By [@bradshannon](https://x.com/bradshannon). [Source](https://x.com/bradshannon/status/2094260531305578886)

## Hosting and sharing our templates

GitHub can host these Markdown setup prompts. Once this repository is pushed, every `templates/*.md` file will have a public URL people can read and copy.

One-click installation requires a Grok-hosted share:

1. Create the Bot inside Grok Bot.
2. Paste and adapt the corresponding Markdown setup brief.
3. Connect the minimum required tools and run a supervised test.
4. Remove private data, internal URLs, credentials, and organization-specific memory.
5. Use **Share Bot** to generate its public `x.ai/bot/...` URL.
6. Add that URL beside the hosted prompt in this README.

GitHub cannot generate or emulate that install link; the live Bot must be created and shared through Grok Bot.

> [!CAUTION]
> Keep sending, spending, signing, deleting, deploying, production changes, access changes, and externally published conclusions behind explicit human approval.

## Contributing

Contribute either an original knowledge-work blueprint or a verified public template. Sources may be GitHub repositories, creator websites, documentation, blogs, demos, X, or other public primary sources—not only social media.

See [CONTRIBUTING.md](CONTRIBUTING.md) for the structure, evidence, and attribution requirements.

## Resources

- [Grok Bot overview](https://docs.x.ai/grok-bot)
- [Create and manage Bots](https://docs.x.ai/grok-bot/bots)
- [Skills and routines](https://docs.x.ai/grok-bot/skills-routines-and-automations)
- [Approvals, security, and privacy](https://docs.x.ai/grok-bot/approvals-security-and-privacy)
- [RongleCat/awesome-grok-bot](https://github.com/RongleCat/awesome-grok-bot) — broad field-case and resource index
- [majiayu000/awesome-grok-bot](https://github.com/majiayu000/awesome-grok-bot) — live public share index and machine-readable catalog

## Disclaimer

This independent community project is not affiliated with or endorsed by xAI, X, Cursor, or any listed creator. Blueprints are operational starting points, not professional legal, financial, medical, security, or compliance advice. Public templates can change after review.

## License

The repository's original blueprints, index metadata, and summaries are released under [CC0 1.0 Universal](LICENSE). Linked third-party templates and source material remain under their respective owners' terms.
