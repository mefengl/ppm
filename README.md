# ppm (pnpm Package Manager)

## Description

This repository contains a command-line tool called `ppm` (pnpm Package Manager) to automate the installation and uninstallation of common development tools and packages. The script checks your Node.js version and installs packages using pnpm if the Node.js version is 16.14 or higher, otherwise, it uses npm for installation.

## Usage

use it now by copying the global-npm-packages.sh file and modifying the packages array

0. Alias the `ppm` command in your shell profile:

```
alias ppm='sh /path/to/ppm.sh'
```

1. Run the `ppm` command to install the defined packages:

```
ppm
```

2. To uninstall the packages, run the `ppm` command with the `-u` flag:

```
ppm -u
```

## Customizing the Script

You can customize the list of packages to be installed by modifying the `packages` array in the `ppm` script. Add or remove package names as needed.

Example:

```
packages=(
  "yarn"
  "vercel"
  "turbo"
)
```

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
