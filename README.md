# Laptop

Laptop is a script to set up a macOS laptop for web and mobile development.

It can be run multiple times on the same machine safely. It installs, upgrades, or skips packages based on what is already installed on the machine.
Requirements

## Install

Download the script:

```bash
curl --remote-name https://raw.githubusercontent.com/kforsthoevel/laptop/master/mac
```

Review the script (avoid running scripts you haven't read!):

````bash
less mac
````

Execute the downloaded script:

````bash
./mac 2>&1 | tee ~/laptop.log
````

Optionally, review the log:

```bash
less ~/laptop.log
```

## What it sets up

* Xcode command line tools
* My dotfiles
* Homebrew
* Ruby
* Python
* Golang

Downloading these packages:

* Hack font
* Docker
* Firefox
* Google Chrome
* Slack
* Keybase
