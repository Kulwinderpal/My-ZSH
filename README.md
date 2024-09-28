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

After thats done you need to install bat if your on Arch,NixOs,and Opensuse on Ubuntu,Debian,and Fedora you need rust-bat (for more distros see https://repology.org/project/bat-cat/versions)

You also need fastfetch which in most Distros that Ship it in their Official repos is fastfetch on debian 12/Ubuntu 24.04 and lower you have to get a Deb from https://github.com/fastfetch-cli/fastfetch/releases
