# Turnkey Linux - Proxmox Backup Server (PBS)

This is a Turnkey Linux (TKL) application for configuring and installing the Proxmox Backup Server (PBS) on a Debian Bookworm environment.

## Features

- Automatically sets up Debian and Proxmox Backup Server repositories.
- Installs the `proxmox-backup` package to configure PBS.
- Includes support for the no-subscription PBS repository.

## Usage

After building and installing the application, you can access Proxmox Backup Server at:

https://{container_ip}:8007

Replace `{container_ip}` with the IP of the container or VM where the application is running.
