# Contributing

To propose a change, create a branch, commit your work, and open a pull request.

## Branch

Create a topic branch off the main branch. Use a short name that describes the change.

```bash
git checkout main
git pull
git checkout -b my-topic-branch
```

## Commit

Make small commits. Give each one a clear one-line message that says what changed.

```bash
git add <changed-files>
git commit -m "Describe the change in one line"
```

## Pull Request

Push the branch and open a pull request against the main branch. Describe the change and why it is needed so reviewers can follow it.

```bash
git push -u origin my-topic-branch
```
