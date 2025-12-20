# Globals

Using a repo to configure and regularly update global npm packages

## What it does

1. Installs the following packages (locally):
- [sfw](https://npmjs.com/package/sfw) aka [Socker Firewall Free](https://docs.socket.dev/docs/socket-firewall-free)

2. Adds `node_modules/.bin` to your PATH
3. If the dependencies are installed when a shell is started,
   prefixes the following binaries with `sfw`: `npm`, `pnpm`, `yarn`, `pip`, `uv`, `cargo`

## Usage

1. Clone the repo
2. install and [mise](https://mise.jdx.dev/installing-mise.html) (make sure to activate it)
3. when mise is configured correctly and you cd into the directory
   you will see some output from `git pull` and `pnpm i`.
   (if not, `mise` is not installed or not activated in your `~/.bashrc`)
4. only once execute the following to add the alises:
   ```bash
   echo ". $PWD/alias" >> ~/.bashrc
   ```
5. restart your terminal(s) for the changes ot take effect
6. you are notified about dependency updates in the repo,
`cd`ing into this directory pulls the updates, updates the dependencies.
