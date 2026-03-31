# Contributing to Agentic Stacks

Thanks for your interest in contributing!

## Ways to Contribute

### Use a Stack and Report Issues

The most valuable feedback comes from real usage. Pull a stack, use it with an agent, and let us know what works and what doesn't.

### Author a Stack

Have deep expertise in a domain? Package it as a stack. See the [authoring guide](https://www.agentic-stacks.com/docs/authoring) for how to create one.

```bash
agentic-stacks create your-org/your-stack
```

### Submit a Stack to the Registry

Third-party stacks don't need to be in the `agentic-stacks` org. Create your stack in your own repo, then open a PR to the [registry](https://github.com/agentic-stacks/registry) adding your formula to `stacks/<your-org>/<name>.yaml`.

### Improve the Platform

The [agentic-stacks](https://github.com/agentic-stacks/agentic-stacks) repo contains the CLI, registry, and website. To contribute:

1. Fork the repo
2. Create a feature branch
3. Install dev dependencies: `pip install -e ".[dev,local,mcp]"`
4. Run tests: `pytest -v --tb=short`
5. Open a PR

### Report Bugs

Open an issue on the relevant repo:
- **CLI / Platform**: [agentic-stacks/agentic-stacks](https://github.com/agentic-stacks/agentic-stacks/issues)
- **Specific stack**: the stack's own repo

## Guidelines

- Keep PRs focused — one feature or fix per PR
- Include tests for new functionality
- Follow existing code patterns and naming conventions
- Stack content should be verified against official documentation

## License

By contributing, you agree that your contributions will be licensed under the MIT License.
