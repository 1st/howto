# HowTo in Programming

## Bash

### Default value

```sh
# Returns "local" if not defined
ENV_NAME="${ENV:-local}"

# Returns "local" if not defined + sets it to the original ENV variable
ENV_NAME="${ENV:=local}"
```
