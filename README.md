# create-pr-action

## Summary

This action creates a pull request to the temporary target branch with the changes in the source branch.

## Usage

```yaml
- name: Create PR
  uses: kakikubo/create-pr-action@v1
  with:
    message: Test
```

## Inputs

### `message`

Specifies the message used for the title and body of the pull request.

## Outputs

### `branch`

The name of the temporary target branch.

## Actions Permissions

requires check of `Allow GitHub Actions to create and approve pull requests` on 'Actions permissions'.
