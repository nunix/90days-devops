# 90 Days of DevOps - Community Edition

This repo contains the files mentioned in the [90 Days of DevOps - Community Edition](https://www.youtube.com/@90DaysOfDevOps) video: [DevOps with Windows].

## Available files

There's two main files in this repo:

- `.wslconfig`: This file contains the configuration for WSL2. It's a hidden file, so you need to enable the option to see hidden files in your file explorer. This file is located in your Windows user folder. If you don't have it, you can create it and add the content from the file in this repo.

- `pkgs-import.json`: This file contains the list of packages that you can import with Winget. You can import it by running the following command in PowerShell: `winget import -i pkgs-import.json`. This will install all the packages listed in the file.

## Useful Links

Windows Terminal:
- [Microsoft Learn](https://docs.microsoft.com/en-us/windows/terminal/)
- [Github repo](https://github.com/microsoft/terminal)

Winget:
- [Microsoft Learn](https://docs.microsoft.com/en-us/windows/package-manager/winget/)
- [Github repo](https://github.com/microsoft/winget-cli)
- [Github community packages repo](https://github.com/microsoft/winget-pkgs)

Git bash:
- [Git for Windows](https://gitforwindows.org/)
- [Github repo](https://github.com/git-for-windows/git)

WSL2:
- [Microsoft Learn](https://docs.microsoft.com/en-us/windows/wsl/)
- [WSL config](https://docs.microsoft.com/en-us/windows/wsl/wsl-config)
- [Github repo](https://github.com/Microsoft/WSL)
- [Github kernel repo](https://github.com/Microsoft/WSL2-Linux-Kernel)

DevHome:
- [Microsoft Learn](https://learn.microsoft.com/en-us/windows/dev-home/)
- [GitHub](https://github.com/microsoft/devhome)

Rancher Desktop:
- [Website](https://rancherdesktop.io/)
- [Docs](https://docs.rancherdesktop.io/)
- [Github repo](https://github.com/rancher-sandbox/rancher-desktop)

Docker Desktop:
- [Website](https://www.docker.com/products/docker-desktop)
- [Docs](https://docs.docker.com/desktop/)
- [Github repo](https://github.com/docker/for-win)

Podman Desktop:
- [Website](https://podman-desktop.io/)
- [Docs](https://podman-desktop.io/docs/)
- [Github repo](https://github.com/containers/podman-desktop)

Finch:
- [Docs](https://runfinch.com/)
- [Github repo](https://github.com/runfinch/finch)