# Follow-through rules

Use this after the evidence-based review. The purpose is to help the user act on useful questions without pretending to know what happened outside the supplied sources.

## Evidence boundary

- Track an earlier question only when its exact wording appears in an earlier review, checklist, message, transcript, or note supplied in the current scope.
- Mark an item `Done` only when a later source directly shows that the question was asked, answered, or the underlying issue was resolved.
- Keep an item in `To-do` when no direct evidence was supplied. Silence is not evidence that the user ignored it.
- If the question was asked but the source contains no clear answer, keep it in `To-do` and state that the question was asked but no answer was found.
- State `Not found in the supplied sources` when the evidence does not show whether a question was asked.
- Do not use `In progress`, percentages, or implied completion.

## Route each open item

Choose one route:

- `Ask client` when the answer requires the other party's goals, decision, approval, context, or commitment.
- `Internal check` when the user can verify a system, document, delivery, owner, date, or existing decision before asking the client.
- `Reflect` when the question is for the user before making a decision or commitment.
- `Notice` when no immediate action is supported.

Do not invent a repair. An internal action must follow directly from the evidence and stay within the user's control.

## Output

Use these sections after the findings:

```markdown
## Done

- [x] [Exact earlier question]
  - Evidence it was asked or addressed: [Short source-backed statement and source.]

## To-do

- [ ] [Exact current or unresolved earlier question]
  - Earlier wording used: [Exact wording, or `No earlier wording was supplied.`]
  - Evidence it was asked: [Source-backed statement, or `Not found in the supplied sources.`]
  - Route: [Ask client | Internal check | Reflect | Notice]
  - Next step: [One concrete action.]

## Copy-ready client message

[A short Slack or email draft containing only the highest-priority `Ask client` questions. Use a neutral greeting or a supplied name. Ask no more than three questions.]

## Copy-ready internal message

[A short draft for an internal stakeholder when a supported internal question needs an answer.]

## Internal actions

- [ ] [A supported internal check or repair that does not require a client answer.]
```

Use `- None supported by the supplied evidence.` when a section has no items. Do not create a client or internal message when no matching outward-facing question is supported. State that plainly instead.

The copy-ready message is a draft. Never send it automatically.
