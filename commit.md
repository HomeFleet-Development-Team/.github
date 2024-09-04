# Semantic Commit Messages

Format: `<type>(<scope>): <subject>`

`<scope>` is optional

## Example

```
feat: add hat wobble
^--^  ^------------^
|     |
|     +-> Summary in present tense.
|
+-------> Type: chore, docs, feat, fix, refactor.
```

More Examples:

- `feat`: (new production feature/element)
- `fix`: (bug/issue fix in production, if not for production it's a chore)
- `docs`: (changes to the documentation)
- `style`: (formatting, blueprint cleanup, etc; no behavioural changes)
- `refactor`: (refactoring assets or blueprints, eg. renaming a variable or an asset)
- `chore`: (updating .gitignore, etc; no production code change)

References:

- https://www.conventionalcommits.org/
- https://seesparkbox.com/foundry/semantic_commit_messages
- http://karma-runner.github.io/1.0/dev/git-commit-msg.html
