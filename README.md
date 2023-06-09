# tailscale-ssh

This project provides a streamlined and user-friendly Command Line Interface (CLI) to manage and
simplify your SSH connections before connecting to servers in your Tailscale network.

## Get Started

```
curl -L https://ssh.succinct.xyz | bash
```

Source your bash config (i.e., `~/.zshrc` or `~/.bashrc`) or start a new terminal session.

```
tsh
```

## Example

```
Tailscale SSH v0.0.1

Select one option using up/down keys and enter to confirm:

   john
   kevin
   chris

Username: ubuntu

Running SSH Command...
  ssh -A ubuntu@kevin
```

## Acknowledgements

- [Alexander Klimetschek](https://unix.stackexchange.com/a/415155) for the bash selector script.
- [Foundry](https://raw.githubusercontent.com/foundry-rs/foundry/master/foundryup/install) for the install script.
