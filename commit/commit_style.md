# Semantic Commit Messages - Extended

[English](https://github.com/jbnu-coda/coda-code-templates/blob/main/commit/commit_style.md) | [한글](https://github.com/jbnu-coda/coda-code-templates/blob/main/commit/commit_style_ko.md)

See how a minor change to your commit message style can make you a better programmer.

Adding a clear range indicator in the middle makes it even easier to see.

Format: `<type>: (<scope>): <subject>`

`<scope>` is optional

## Example

```
feat: Main.java: add hat wobble
^--^  ^-------^  ^------------^
|     |          | 
|     |          +-> Summary in present tense.
|     |
|     +------> Write a clear scope.
|
+-------> Type: chore, docs, feat, fix, refactor, style, or test.
```

More Examples:

- `feat`: (new feature for the user, not a new feature for build script)
- `fix`: (bug fix for the user, not a fix to a build script)
- `docs`: (changes to the documentation)
- `style`: (formatting, missing semi colons, etc; no production code change)
- `refactor`: (refactoring production code, eg. renaming a variable)
- `test`: (adding missing tests, refactoring tests; no production code change)
- `chore`: (updating grunt tasks etc; no production code change)

References:

- https://gist.github.com/joshbuchea/6f47e86d2510bce28f8e7f42ae84c716
- https://www.conventionalcommits.org/
- https://seesparkbox.com/foundry/semantic_commit_messages
- http://karma-runner.github.io/1.0/dev/git-commit-msg.html