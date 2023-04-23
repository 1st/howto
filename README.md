# HowTo in Programming

## Bash

### Use default value

```sh
# Returns "local" if not defined
ENV_NAME="${ENV:-local}"

# Returns "local" if not defined + sets it to the original ENV variable
ENV_NAME="${ENV:=local}"
```

### Remove all files by the given pattern 

```sh
find . -name "*.bak" -type f -delete
```

Find [more examples](https://linuxhint.com/remove-all-files-with-extension-linux-command-line/)

### Empty file content

```sh
sudo truncate -s 0 /var/log/nginx/access.log
sudo truncate -s 0 /var/log/**/*.log
```
