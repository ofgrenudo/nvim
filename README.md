# NVIM Config Installation

Note, this is still in its experimental phases. Currently, to use my config files you will need the following installed onto your system.

- Packer
- Curl or Git (for treesitter)
- A C compiler in your path with libstdc++ (for treesitter please visit their github and read Quickstart/Requirements)

## Installation

1. Install Neovim with `winget install neovim`.
2. Install Zig by downloading it from their website and then Extracting it to a folder and updating your $PATH.
3. Download and Install a Nerdfont (preferably for me the Agave font)
4. Configure Windows Terminal (wt.exe) with the Nerdfont as default ([or use my conf here](https://github.com/ofgrenudo/confs/blob/main/configurations/wt_conf.json))
5. Navigate into `~\AppData\Local\` and `git clone https://github.com/ofgrenudo/nvim.git`

## Usage

Ctrl + N        Opens the file browser.
Ctrl + W        Shifts focus from the file to the file browser and vice versa.
Space Space     Searches Files.
Ctrl + P        Find Files.

## Tips

:vsplit | terminal      Opens a Terminal.



