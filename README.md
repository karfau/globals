# Globals

Using a repo to configure and regularly update global npm packages

## Usage

1. Clone the repo
2. install and [mise](https://mise.jdx.dev/installing-mise.html) (make sure to activate it)
3. when mise is configured correctly and you cd into the directory
   you will see some output from `git fetch`, `git status` and `pnpm i`.
   (if not mise is not installed or activated in your `~/.bashrc`)
4. only once execute the following to add the alises:
   ```bash
   echo ". $PWD/alias" >> ~/.bashrc
   ```
## 