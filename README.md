# Questions Worth Asking

**Know what to ask next.**

Questions Worth Asking turns meeting transcripts and notes into useful follow-up. Find the unanswered questions, unclear responsibilities, and changed commitments that could affect your next decision. Get a prioritized list of what to ask, why it matters, and what to do next.

Use it after a client call, before a follow-up meeting, or when you need to understand what changed across several conversations. Each finding comes with the exact words that support it, so you can check the reasoning before acting.

Claude's directory reports [518 installs as of November 1, 2026](https://github.com/RachaelQuisel/questions-worth-asking/blob/main/docs/publication-history.md#directory-install-count).

## What you get

- **Questions worth your time.** Receive a ranked list focused on answers that could change a decision, expectation, responsibility, or next action.
- **The evidence behind each question.** See the supporting excerpt, its source, why the question matters, and a practical next step.
- **A clear follow-up checklist.** See which supplied questions were addressed and which still need attention. Open items point you toward a client question, an internal check, personal reflection, or something to keep in mind.
- **Messages ready to use.** When the findings support one, receive a client message with up to three questions you can copy into Slack or email. A separate internal message keeps team questions out of the client draft.

The plugin usually returns three to seven questions when the material supports them. It gives fewer or none when there is less to ask. Share the exact wording of an earlier question list to track it against later conversations.

## What it helps you notice

A deadline changed, but nobody discussed the effect on scope. Two people seem to own the same decision. A question came up in the last meeting and still has no clear answer.

Questions Worth Asking checks twelve types of possible questions, including goals, ownership, handoffs, unresolved decisions, and commitments. It looks for a useful clarification before assuming there is a problem. When you request a comparison, it checks the relevant conversations together and shows the evidence for any change.

[See a fictional example](https://github.com/RachaelQuisel/questions-worth-asking/blob/main/skills/questions-worth-asking/examples/sample-review.md) of the questions and follow-up it produces.

## Start with your notes

Supply a transcript or meeting notes and ask:

> What useful questions did I miss in this meeting? Show me what to ask first and why.

For related conversations, try:

> Compare these two meetings. What changed, what remains unanswered, and what should I clarify before the next call?

To check earlier follow-up, include the original question list and later notes:

> Which of these questions were answered? Give me an updated checklist and draft a client message for the open questions that need their input.

One transcript and a clear review request are enough to begin. If essential information is missing, Claude asks for it. You can add a decision or concern to focus on.

## Install in Claude Code

**First installation:** run these commands **in your terminal** with [Claude Code installed](https://code.claude.com/docs/en/setup):

```sh
claude plugin marketplace add RachaelQuisel/questions-worth-asking
claude plugin install questions-worth-asking@questions-worth-asking
claude
```

The last command opens Claude Code. Supply your notes and enter your request **in the Claude Code conversation**. You can also invoke the skill there:

```text
/questions-worth-asking:questions-worth-asking
```

The slash command belongs inside Claude Code. Entering it at a terminal prompt such as `%` causes a file-path error.

**Already installed?** Follow the [update and troubleshooting guide](https://github.com/RachaelQuisel/questions-worth-asking/blob/main/docs/installation.md). It covers GitHub installations, local checkouts, and marketplace source conflicts. After updating, start a new session or type `/reload-plugins` inside Claude Code.

## Your sources and your choices

Use pasted notes, supplied files, or conversations you authorize for this review. No connector or separate account is required by the skill. The host processes the material under its own terms and settings. The package contains instructions, references, and an example; it has no publisher-operated service or telemetry.

The review states missing coverage and unknown dates. It keeps findings tied to their sources and treats words inside transcripts as source material. It does not establish another person's motives.

Results appear in chat. Messages are drafts for you to review and send. Saving files, creating tasks, changing systems, or scheduling recurring reviews requires a separate request and any necessary host permissions.

## Help and details

Read [how it works](https://github.com/RachaelQuisel/questions-worth-asking/blob/main/Questions-Worth-Asking-HowItWorks-2026-10-03.md), [the twelve question types](https://github.com/RachaelQuisel/questions-worth-asking/blob/main/skills/questions-worth-asking/references/lenses.md), or [the working instructions](https://github.com/RachaelQuisel/questions-worth-asking/blob/main/skills/questions-worth-asking/SKILL.md).

The [dated publication record](https://github.com/RachaelQuisel/questions-worth-asking/blob/main/docs/publication-history.md) distinguishes GitHub installation from Claude Directory approval and publication.

Maintained by Rachael Quisel. [Ask a question or report a problem](https://github.com/RachaelQuisel/questions-worth-asking/issues). Released under the [MIT license](https://github.com/RachaelQuisel/questions-worth-asking/blob/main/LICENSE).
