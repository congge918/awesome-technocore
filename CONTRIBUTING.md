# Contributing to Awesome Technocore

Thanks for helping improve Awesome Technocore. Contributions should make the
list more useful, accurate, and safe for people working with Technocore Chat.

## Before suggesting a project

A project should:

- directly integrate with, analyze, document, or extend Technocore Chat;
- provide meaningful public source code or substantial documentation;
- have a clear purpose that is not already covered by a stronger entry;
- follow the current upstream protocol and document important trust limits;
- handle identities and private keys safely;
- use a clear open-source license; and
- be maintained, publicly accessible, and ready for people to use or evaluate.

Do not submit:

- empty repositories, profile pages, personal proof records, or simple forks;
- copied or near-duplicate onboarding guides;
- projects that request wallet seeds, unrelated private keys, or other secrets;
- projects promising guaranteed airdrops, rewards, or official affiliation;
- unrelated projects that only mention Technocore; or
- archived, abandoned, undocumented, or broken projects.

## Choose the right section

- **Guides and localization** — Onboarding guides, tutorials, and translations.
- **Clients and SDKs** — Libraries, command-line clients, MCP servers, and agent
  integrations.
- **Identity, signing, and verification** — DID creation, key management,
  signing, receipts, and verification tools.
- **Monitoring and research** — Analytics, observability, archives,
  conformance tests, measurements, and protocol research.
- **Operations and deployment** — Self-hosting, hardening, maintenance, and
  operator tooling.
- **Experiments and applications** — Working products and focused demonstrations
  built on Technocore.

If a project fits several sections, add it only to the section representing its
primary purpose.

## Entry format

Use one bullet with the GitHub repository and an objective description:

```markdown
- [owner/repository](https://github.com/owner/repository) — Concise description
  of what the project provides and who it helps.
```

Descriptions should:

- begin with an uppercase letter and end with a period;
- explain the concrete benefit instead of repeating the repository name;
- mention the language or platform when that helps readers choose; and
- avoid promotional language, star counts, reward claims, and unsupported
  superlatives.

Maintainers determine placement based on practical usefulness, protocol
correctness, supporting evidence, documentation, and breadth of use. Specialized
projects are welcome and normally follow more broadly applicable resources.

## Pull request checklist

Before opening a pull request, confirm that:

- [ ] The repository meets every inclusion requirement above.
- [ ] You searched the README for duplicate or equivalent entries.
- [ ] The link points to the project's main public repository.
- [ ] The project was checked against the current upstream documentation.
- [ ] The description is factual, concise, and grammatically complete.
- [ ] The entry appears in the most relevant section.
- [ ] No unrelated files or formatting were changed.
- [ ] `README.md` and `CONTRIBUTING.md` pass Markdown linting.

In the pull request description, explain what the project uniquely provides and
mention any tests, protocol vectors, reproducible evidence, or security
documentation that support its inclusion.

## Updating or removing an entry

Corrections and removals are welcome. Include evidence when reporting a broken
link, unsafe behavior, incorrect protocol claim, abandoned project, or stronger
replacement. When a project becomes obsolete, update or remove its entry rather
than adding a compatibility note for superseded behavior.

Each linked project retains its own license and terms.
