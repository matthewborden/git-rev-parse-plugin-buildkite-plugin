# Git Rev Parse Buildkite Plugin

Resolve the current commit

## Example

Add the following to your `pipeline.yml`:

```yml
steps:
  - command: ls
    plugins:
      - matthewborden/git-rev-parse-plugin#v1.0.0
```

## Contributing

1. Fork the repo
2. Make the changes
3. Run the tests
4. Commit and push your changes
5. Send a pull request