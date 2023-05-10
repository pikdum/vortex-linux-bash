# vortex-linux

> **Note:** This tool is a work in progress.

## Description

vortex-linux is a CLI tool that simplifies running Vortex, the popular mod manager for games, on Linux. It streamlines the setup of Wine, handles dependencies, and provides commands for installing, launching, and uninstalling Vortex.

## Prerequisites

- Linux operating system
- Bash shell
- `curl` command-line tool

## Installation

1. Download the `vortex-linux` file.

```shell
curl -LO https://raw.githubusercontent.com/pikdum/vortex-linux/master/vortex-linux
```

2. Make the file executable.

```shell
chmod +x vortex-linux
```

3. Place the `vortex-linux` file in a directory listed in your `$PATH`.

## Usage

Run the `vortex-linux` command followed by the desired action:

```shell
vortex-linux [command]
```

Available commands:

- `install`: Set up dependencies and install Vortex.
- `start`: Launch Vortex.
- `uninstall`: Remove Vortex.
- `update`: Fetch the latest Wine, Vortex, and game mappings.

**Note:** Ensure that the `vortex-linux` file has execute permissions (e.g., `chmod +x vortex-linux`) before running any commands.
