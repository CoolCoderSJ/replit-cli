# Replit CLI
![logo](https://sjcdn.is-a.dev/file/ravjqk)

```
pip install repl-cli
```
Welcome to Replit CLI! With the Replit CLI Application, you can work with your repls locally, including clone, pull, and push, the core features of the CLI. The full list of features includes-

```
PS C:\> replit
Usage: replit [OPTIONS] COMMAND [ARGS]...

Options:
  --install-completion [bash|zsh|fish|powershell|pwsh]
								  Install completion for the specified shell.
  --show-completion [bash|zsh|fish|powershell|pwsh]
								  Show completion for the specified shell, to
								  copy it or customize the installation.

  --help                          Show this message and exit.

Commands:
  clone    Clone a Repl's contents to your local machine
  db       Edit the Replit DB for a Repl
  env      Interact with the Environment of the Repl of the Current Working...
  exec     Execute a command to run on the remote repl.
  login    Authenticate with Replit CLI.
  pull     Pull the remote contents of the repl inside the working...
  push     Push changes to the server and override remote.
  run      Run, Stop, or Restart a Repl from your local machine.
  shell    Connect to a bash shell with a remote repl.
  user     Lookup the details for a Replit User
  version  Output the current version for Replit CLI
PS C:\>
```

## Installation
- Make sure you have Python 3.6 or higher installed. To do so, type `python` inside of a Command Prompt/Terminal instance. If you have Python installed, a Python shell will come up with the version number. (type ` quit() ` inside of the python shell to quit it) If you do not have Python 3.6+ or do not have Python at all, you can install it by downloading the installer for your platform located [here](https://www.python.org/downloads/)
- Once you have python, run the following command- ` pip install repl-cli `, preferably with Administrator access (Unix platforms do not need admin access, and `Run as Administrator` on Windows) to make sure that your PC recognizes Replit CLI properly. 
- Once installed, type `replit` into a shell to get started!

## Documentation
To see the docs and for more information, click [here](https://replitcli.repl.co)

## Building From Source
To build from source, run the following commands-
```
git clone https://github.com/CoolCoderSJ/Replit-CLI.git
cd .\replit-cli\replit_cli
python main.py
```

## Credits
Thanks to the many people who helped grow this project-
- @Codemonkey51 and @turbio for help with Crosis, the Replit API
- @SpotandJake for help with the JS server counterpart, used for some operations.
- @sugarfi for the initial Python Client for Crosis. (This has been tampered with and published to PyPI)
- And everyone on the [Replit Discord Server](https://replit.com/discord) for the motivation, and general help.
