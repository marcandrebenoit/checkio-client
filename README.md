checkio-client fork
===================


## About this fork
The original branch won't install onto current up to date systems mainly because the requirements.txt is out of date with the current version numbers and uses == instead of ­>= for its miminum versions to be using.
The pip3 install --upgrade checkio_client (or pipx install --upgrade checkio_client) will not work for similar reasons.

## Current install instructions for Ubuntu 24.04 and up.

```bash
git clone https://github.com/marcandrebenoit/checkio-client.git
...
cd checkio-client
pipx install .
```

Command-line tool for playing [**CheckiO games**](https://checkio.org).

[**CheckiO**](https://checkio.org) - Coding games for beginners and advanced programmers where you can improve your coding skills by solving engaging challenges.
