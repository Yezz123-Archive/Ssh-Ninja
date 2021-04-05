# SSH-Ninja

- Just a simple SSH brute-force script a week-end fun concept after reading Pexpect Docs.

- Tested against an OpenSSH 7.9 server with no issues; as this script was more for personal use I haven't tested it thoroughly.

- I use `pxssh` is a Python module based on Pexpect for establishing SSH connections. Its class extends `pexpect.spawn` to specialize setting up SSH connections.

- Is a specialized module that provides specific methods to interact directly with SSH sessions such as `login()`, `logout()`, and `prompt()`.

- You can install [Pexpect](https://github.com/pexpect/pexpect) using pip:
```
pip install pexpect
```