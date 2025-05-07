# Cursor Project Development Rules

This document outlines the strict development workflow and rules that must be followed when working on this project using Cursor IDE.

## Core Principles

1. **Strict Adherence to Process**
   - Every interaction must begin with a review of these rules
   - All steps must be followed in exact order
   - No assumptions about requirements
   - No skipping of verification steps

2. **Documentation First**
   - All development must be aligned with the development plan
   - Documentation must be kept up-to-date
   - Tasks must be properly marked as completed

3. **Quality Assurance**
   - All steps must be verified before proceeding
   - Deviations must be documented and corrected
   - Clarification must be sought for any ambiguity

## Development Workflow

### 1. Documentation Review
Before starting any work, developers must:
- Review the development plan (`simpleList/Documentation/DEVELOPMENT_PLAN.md`)
- Read the app description (`simpleList/Documentation/app_description.txt`)
- Verify the current development phase

### 2. Branch Management
Ensure proper branch workflow:
- Verify current branch
- Confirm branch type (feature/foundation/bugfix)
- Validate branch naming convention
- Check branch source (develop/main)

### 3. Implementation Planning
Before coding:
- Cross-reference with development plan
- Verify technical requirements
- Review code structure requirements
- Check naming conventions
- Validate against app description

### 4. Approval Process
Before making changes:
- Present complete implementation plan
- Wait for explicit approval
- Confirm all requirements are met
- Verify no steps were skipped

## Git Workflow Rules

### Branch Naming Conventions
- `main`: Production-ready code
- `develop`: Integration branch for features
- `foundation/*`: Core setup and infrastructure branches
- `feature/*`: New features (e.g., feature/user-auth)
- `bugfix/*`: Bug fixes (e.g., bugfix/login-crash)
- `hotfix/*`: Emergency production fixes
- `release/*`: Release preparation

### Branch Workflow
1. **Branch Creation**
   - Branch off from:
     - `develop` (for features)
     - `main` (for hotfixes)
     - `foundation` (for core infrastructure)
   - Use descriptive names with type prefix
   - Include ticket/issue number if applicable
   - Use lowercase and hyphens for readability

2. **Commit Guidelines**
   - Write clear commit messages
   - Use conventional commits format:
     - `feat`: New features
     - `fix`: Bug fixes
     - `docs`: Documentation
     - `style`: Formatting
     - `refactor`: Code restructuring
     - `test`: Test addition/modification
     - `chore`: Maintenance

3. **Merge Requirements**
   - All tests must pass
   - Code review required
   - No merge conflicts
   - Up-to-date with base branch
   - Proper documentation updated

4. **Protected Branches**
   - `main`: Requires PR and review
   - `develop`: Requires PR and review
   - `foundation/*`: Requires PR and review

5. **Release Process**
   - Create release branch from develop
   - Version bump and changelog
   - Final testing and review
   - Merge to main with tag
   - Merge back to develop

6. **Emergency Fixes**
   - Hotfix branches from main
   - Immediate review priority
   - Merge to main AND develop

## Important Warnings

- ⚠️ Never proceed to the next step without completing the previous one
- ⚠️ Never assume approval
- ⚠️ Never make changes without following all steps
- ⚠️ Stop and ask for clarification if any step is unclear

## Documentation Updates

After completing any task:
1. Update `simpleList/Documentation/DEVELOPMENT_PLAN.md`
2. Mark completed tasks with [x]
3. Verify the development plan is current before proceeding

## Getting Help

If you encounter any ambiguity or uncertainty:
1. Stop immediately
2. Document the issue
3. Request clarification
4. Wait for explicit guidance before proceeding

---

Remember: These rules are designed to maintain consistency and quality in development. Following them strictly ensures the project's success and maintainability. 