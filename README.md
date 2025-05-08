# Cursor Project Rules

This repository contains a collection of rules and standards for Cursor IDE projects. These rules help maintain consistency, quality, and best practices across development workflows.

## Repository Structure

```
.
├── .cursor/
│   └── rules/           # Cursor rule files
├── cursor-rules-location.mdc  # Rules for Cursor rule file placement
├── swift-standards.mdc        # Swift coding standards
├── project-rules.mdc          # Core project workflow rules
├── git-rules.mdc             # Git workflow and branch management rules
└── README.md                 # This file
```

## Rule Files

### 1. Cursor Rules Location (`cursor-rules-location.mdc`)
- Defines standards for placing and organizing Cursor rule files
- Specifies the correct directory structure (`.cursor/rules/`)
- Enforces naming conventions for rule files
- Ensures proper organization of rule files within the project

### 2. Swift Standards (`swift-standards.mdc`)
- Comprehensive Swift coding standards and best practices
- Covers code organization, error handling, testing, documentation, and performance
- Enforces Swift API Design Guidelines
- Includes examples of good and bad practices

### 3. Project Rules (`project-rules.mdc`)
- Core project development workflow requirements
- Mandatory review checklist for all actions
- Documentation review requirements
- Branch workflow verification
- Implementation planning guidelines
- Approval process requirements

### 4. Git Rules (`git-rules.mdc`)
- Branch naming conventions and management
- Branch workflow rules
- Commit guidelines and conventional commits
- Merge requirements and code review process
- Branch cleanup and protection rules
- Release process guidelines
- Emergency fix procedures
- Documentation requirements

## Usage

1. Place all Cursor rule files (`.mdc`) in the `.cursor/rules/` directory
2. Follow the naming conventions specified in `cursor-rules-location.mdc`
3. Ensure all rules are properly formatted according to the Cursor rule specification
4. Keep rules up to date with project requirements

## Contributing

When adding or modifying rules:
1. Follow the mandatory review checklist in `project-rules.mdc`
2. Ensure proper placement in `.cursor/rules/` directory
3. Follow naming conventions
4. Include clear examples and documentation
5. Update this README if necessary

## Version Control

All changes to rules should follow the Git workflow specified in `git-rules.mdc`, including:
- Proper branch naming
- Conventional commits
- Code review process
- Documentation updates

## License

[Specify your license here] 