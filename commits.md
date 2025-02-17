## Commits convention

The commit message should be structured as follows:
```
<type>[optional scope]: <description>
[optional body]
[optional footer(s)]
```

### `<type>`
Required. One of the following:

 Тип   | Описание
:---|:---
init|✨ Beginning of a project or a task
feat|✨ Adding a new functionality
fix|🐛 Bug fixes
docs|📚 Documentation updates
style|💎 Code style changes
refactor|📦 Code refactoring: application functionality wasn't changed
perf|🚀 Performance changes
test|🚨 Adding or changing tests
chore|♻️ Clean up changes

Commit type can contain ! to draw attention to breaking change.

Example: `chore!: drop support for Node 6`

### `(scope)`
Optional. Provide additional contextual information.

Expample: `feat(parser): add ability to parse arrays.`

### `<description>`
Required. Short task description.

### `[body]`
Optional. Short list of changes.

### `[footer]`
Optional. Must follow a convention similar to [git trailer format](https://git-scm.com/docs/git-interpret-trailers).

---
Based on [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/).
