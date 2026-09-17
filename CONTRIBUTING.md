# Contributing to Skeleton Theme

## How to contribute

We ❤️ pull requests. If you'd like to fix a bug, contribute a feature, or just correct a typo, feel free to do so, as long as you follow our [Code of Conduct](./CODE_OF_CONDUCT.md).

If you're thinking of adding a new feature or proposing a new pattern across the theme, please consider opening an issue first. This will allow us to discuss your idea, ensure it aligns with the project's direction, and potentially save you some time.

For your contribution to be accepted, you'll need to sign the [Shopify Contributor License Agreement (CLA)](https://cla.shopify.com/).

## Standards

* This codebase must be minimalist, not a fully featured theme.
* This theme must provide a common foundational starting point for most developers.
* Do not include or reference legacy or non-recommended features.
* All changes must preserve the principles defined in the README.

## Steps to contribute

1. Fork the repository: [https://github.com/Shopify/skeleton-theme/fork](https://github.com/Shopify/skeleton-theme/fork)
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to your branch: `git push origin my-new-feature`
5. Create a new Pull Request

## Commit Conventions

This project follows the [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/) specification, with commit types based on the Angular commit message convention and the additional project-specific use of `chore`.

### Commit Message Format

```
<type>(<scope>): <description>
```

The `scope` is optional.

### Commit Types

| Type | Description |
| --- | --- |
| `build` | Changes that affect the build system or external dependencies, including project configuration and package dependencies. |
| `ci` | Changes to continuous integration configuration and scripts. |
| `chore` | Maintenance tasks that do not modify application functionality, such as auxiliary tools, project configuration, dependency maintenance, or other non-functional changes. |
| `docs` | Documentation-only changes. |
| `feat` | A new feature or functionality. |
| `fix` | A bug fix. |
| `perf` | A code change that improves performance. |
| `refactor` | A code change that neither fixes a bug nor adds a feature. |
| `test` | Adding missing tests or correcting existing tests. |

### Commit Guidelines

- Use lowercase for the commit type.
- Use an imperative, present-tense description.
- Keep the description concise and specific.
- Do not capitalize the first letter of the description.
- Do not add a period at the end of the description.
- Use `feat` when introducing new functionality.
- Use `fix` when correcting a bug.
- Use `docs` for documentation-only changes.
- Use `build` for changes related to the build system, dependencies, or project setup.
- Use `chore` for maintenance and auxiliary changes that do not affect application functionality.
- Use `refactor` when changing the internal structure of the code without changing its behavior.
- Use `perf` when the primary purpose of the change is improving performance.
- Use `test` when adding or modifying tests.
- Use `ci` for continuous integration configuration and scripts.

### References

- [Conventional Commits Specification](https://www.conventionalcommits.org/en/v1.0.0/)
- [Angular Commit Message Guidelines](https://github.com/angular/angular/blob/main/contributing-docs/commit-message-guidelines.md)

The Angular convention defines a specific set of commit types, while Conventional Commits allows additional types. This project includes `chore` as an additional maintenance type.
