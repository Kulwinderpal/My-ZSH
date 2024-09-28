# Installation

To install my personal ZSH configuration, follow these steps:

## Step 1: Install zsh4humans

You first need to install `zsh4humans`. You can do this by running:

```bash
if command -v curl >/dev/null 2>&1; then
  sh -c "$(curl -fsSL https://raw.githubusercontent.com/romkatv/zsh4humans/v5/install)"
else
  sh -c "$(wget -O- https://raw.githubusercontent.com/romkatv/zsh4humans/v5/install)"
fi
```

Step 2: Install bat

After that, you need to install bat. The installation method depends on your distribution:

    Arch, NixOS, and openSUSE: Install bat from your package manager.
    Ubuntu, Debian, and Fedora: Install rust-bat. For more distributions, see Repology.

Step 3: Install fastfetch

You also need fastfetch. In most distributions that ship it in their official repositories, you can install it directly.

    On Debian 12/Ubuntu 24.04 and lower, you will need to download a .deb package from the fastfetch releases page.
