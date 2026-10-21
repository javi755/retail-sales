# My semantic model

## AtScale semantic model

This repo holds an AtScale SML semantic model. The `atscale-comodel` plugin is installed.

- Use `comodel` commands to explore the warehouse, scaffold dataset files and validate
  the project. Run `comodel --help` for the list.
- Run `comodel doctor` before other work. On exit 2, stop and tell a person.
- On `AUTH_FAILED` with the hint "Run comodel login.", ask the person to run
  `! comodel login`. Only a person can log in, so never run it yourself.
- Run `comodel --json validate` after each change. On exit 1, fix the findings and run
  it again.
- Never commit, push or publish on your own. Ask a person first. Publishing stays git +
  Design Center.
