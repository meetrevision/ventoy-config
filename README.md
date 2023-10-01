# Revision Configuration for Ventoy

This is a test repository for automating some parts of the Windows installation process using Ventoy Auto Install Plugin.

## Features

- OOBE configuration
  - Disables online account creation
  - Hides the Network screen
  - Disables the Privacy screen
- A custom Script
  - Disables automatic drivers updating
  - Disables AllowTelemetry
- Disables CEIP and Error Reporting
- Prevents automatic Teams installation
<!-- - Disables dynamic updates and diagnostic data during Windows PE -->

## Usage

1. Download the latest release of [Ventoy](https://github.com/ventoy/Ventoy/releases)
2. Configure Secure Boot and partition style
3. Install Ventoy
4. Copy the contents of this repository to the root of the Ventoy drive
5. Move your Windows ISO file(s) to the `WinISO` folder
6. Boot into Ventoy and select your ISO file
