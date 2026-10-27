### Fixed

- Agents now follow a confirmation rule in any `CLAUDE.md` or `AGENTS.md` file, also when a request
  names the action. Before, an agent could make a change that cannot be undone, such as a Stripe
  setting, without the confirmation that the file asked for.
