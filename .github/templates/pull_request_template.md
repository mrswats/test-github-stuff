## Issue Description

- [ ] What does this Pull Request change?
- [ ] Are the commits messages written in the [Semantic Commit Message](https://gist.github.com/joshbuchea/6f47e86d2510bce28f8e7f42ae84c716) style?
- [ ] Do the commit structure make sense and can be rolled back separately?

## Tests

- [ ] Did you write new tests for this change?
- [ ] Does the coverage covers 100% of the changes?

Run this command to check coverage in the terminal

```
poetry run pytest --color yes --durations=10 --forked -nauto -qk "" --cov --cov-report term
```

## Migrations

- [ ] Does this change require any migrations?
- [ ] Are the migrations made reversible?

## Additional Considerations

- [ ] Does this change require any other additional changes in infrastructure?
- [ ] Does this change require any changes in the environment?

