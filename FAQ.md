# Project FAQ
A simple FAQ to clarify any issues regarding this project.


## How do I update this FAQ?

Create an issue, or fork the FAQ and send a pull request (we can discuss changes and ideas as part of the pull request).


## FAQ

### What is the purpose and goals of this project?
Overall purpose: Collect and coordinate requirements and effort to implement the Elm Language Server.
Goals:
* Coordinate all efforts on Elm Language Server
* Resolve whether or not ElmLS should implement the Language Server Protocol (LSP).
* An initial architecture, components, how the language server will relate to existing and new elm tools.
* A plan for further work on implementation.

### How to contribute?
Check [CONTRIBUTING.md](CONTRIBUTING.md) for details.

### Should comments go on the issues on the repo or in the doc
The document will eventually be tranferred to one/several markdown files. It will contain requirements/references/decisions, while we should also track how important things evolve in the issues. So, we can discuss/comment where appropriate, and then we can copy/track into issues so that we can have a full history of reasoning for any decisions.

### Why have a document outside of a git repository? Markdown is quite good for that and you can have precommit hook to generate toc.
I considered both alternatives and actually started with only a markdown file on the repository. After some initial discussions, we landed on a separate Google Document for now, making it easier to write and comment directly for all. This can be changed back to a markdown document at any time if more people suggest this as a better alternative. Join in on the #elm-langauge-server Slack channel to discuss.


