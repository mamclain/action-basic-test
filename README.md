# action-basic-test

This action prints "Hello World" or "Hello" + the name of a person to greet to the log.

*This action is based off of the [GitHub Actions Docker Example](https://docs.github.com/en/actions/creating-actions/creating-a-docker-container-action).*

## Inputs

## `who-to-greet`

**Required** The name of the person to greet. Default `"World"`.

## Outputs

## `time`

The time we greeted you.

## Example usage
```
uses:mamclain/action-basic-test@v1
with:
  who-to-greet: 'Sarah the Octochicken'
```