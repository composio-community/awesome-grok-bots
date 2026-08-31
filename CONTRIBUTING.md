# Contributing

This repository accepts two kinds of contribution: original knowledge-work blueprints and verified links to public Grok Bot templates.

## Add a blueprint

Add one ordinary Markdown setup brief under `templates/`:

```text
templates/specific-bot-name.md
```

This is a manual copy-paste prompt, not an official Grok import format. State that clearly at the top of the file.

The blueprint must define:

- one durable job and its anti-jobs;
- required inputs and minimum connections;
- a repeatable operating loop;
- concrete, reviewable deliverables;
- source and evidence rules;
- quality checks and escalation conditions;
- explicit approval boundaries;
- a supervised first-run test.

Keep it narrow enough that a reviewer can tell whether it succeeded. “Chief of staff,” “research assistant,” and other generic titles need a specific owned outcome.

Blueprint text must be original or compatibly licensed. Do not copy a public Bot's profile, skills, memory, routines, private data, or secrets.

## Add a public template

A main-list public template must have:

- a live `https://x.ai/bot/...` preview;
- a creator-controlled primary source explaining the Bot;
- one concrete knowledge-work job;
- accurate creator and team attribution;
- a summary written in your own words.

In the pull request, state when you opened both links and what you verified. A demo without an install link may be proposed as research evidence, but not presented as an installable template.

## Out of scope

- novelty, lifestyle, shopping, or personality-only Bots;
- vague general assistants without an owned output;
- spam, deceptive engagement, impersonation, credential theft, or covert surveillance;
- autonomous trading, unsupervised financial actions, or invented financial claims;
- unsupervised production, access, publishing, deletion, signing, or spending;
- copied third-party instructions without permission and compatible licensing.

## Attribution

- Credit every person or organization supported by the public evidence.
- Explain team ownership when a prominent account amplified work created by someone else.
- Prefer creator-controlled sources over roundups.
- If authorship is ambiguous, say so.

## Review bar

Reviewers should be able to answer four questions quickly:

1. What decision or artifact does this Bot own?
2. What evidence does it use and cite?
3. How is quality checked?
4. What can it never do without a human?
