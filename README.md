# Tasker-Automation

A personal collection of **Tasker profiles, tasks, projects, and Android automation ideas** by [@hemant0hack](https://github.com/hemant0hack).

This repository is intended to grow into a practical library of reusable automations—from small daily shortcuts to complete Tasker projects. Public projects will be documented here so they can be understood, adapted, and improved by others.

## What is Tasker?

[Tasker](https://tasker.joaoapps.com/) is an Android automation app that runs actions when defined contexts occur, such as an app opening, a time or location being reached, a device state changing, or an event being triggered. A Tasker automation generally combines:

- **Profiles** — triggers and contexts
- **Tasks** — ordered actions to execute
- **Variables** — reusable values and runtime data
- **Scenes** — custom interfaces and controls
- **Plugins and intents** — integrations with Android and other apps

## Repository goals

- Share useful, reliable Tasker automations
- Keep projects organized and easy to import
- Document prerequisites, permissions, and expected behavior
- Provide simple starting points for learning Tasker
- Maintain a safe boundary between public examples and private personal projects

## Planned organization

As more projects are added, they may be grouped like this:

```text
Tasker-Automation/
├── projects/       # Complete Tasker project exports
├── profiles/       # Standalone profiles and smaller automations
├── tasks/          # Reusable standalone tasks
├── scenes/         # Tasker scenes and UI experiments
├── docs/           # Setup notes, screenshots, and troubleshooting
└── README.md
```

Each shared project should include its purpose, supported Android/Tasker version, required plugins, permissions, setup steps, and known limitations.

## Security and privacy

This is a public repository, but not every personal project should be public. Private or sensitive automations will stay in a private repository or local backup.

**Never commit:** passwords, API keys, access tokens, OTPs, personal addresses, private URLs, device identifiers, exported credentials, or personal notification/SMS data. Use placeholders such as `YOUR_API_TOKEN` in public examples and replace them locally. Review Tasker exports before publishing because they can contain sensitive variables, file paths, and account details.

If you find a security issue, please do not publish secrets in an issue. Use GitHub's private vulnerability-reporting channel when available, or contact the maintainer privately.

## How to use a project

1. Read the project's prerequisites and permission notes.
2. Download or import the Tasker project/profile export.
3. Replace placeholders and configure local variables.
4. Review every profile trigger and action before enabling it.
5. Test it manually, then enable it for normal use.

Always keep a backup of your current Tasker setup before importing an unfamiliar project. Some automations may require accessibility, notification access, location, battery-optimization exemptions, or third-party plugins.

## Contributing

Suggestions, bug reports, and improvements are welcome. When adding an automation, please include:

- A clear name and short description
- The trigger, main actions, and expected result
- Requirements, permissions, and plugin dependencies
- Import/setup instructions
- Screenshots or an example where helpful
- Confirmation that secrets and personal data have been removed

## Useful resources

- [Tasker official website](https://tasker.joaoapps.com/)
- [Tasker Userguide](https://tasker.joaoapps.com/userguide/en/)
- [Tasker tour and examples](https://tasker.joaoapps.com/tour.html)
- [TaskerNet](https://taskernet.com/) for sharing and discovering Tasker projects

## License

This repository is available under the [MIT License](LICENSE), unless a project states otherwise.