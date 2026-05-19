# MCP Registry – City of Stirling

This repository contains the approved Model Context Protocol (MCP) servers for use with GitHub Copilot within the City of Stirling environment.

## Purpose

This repository enforces governance over which MCP servers are permitted. Only servers defined in the `servers.json` file are allowed for use, ensuring:

- Secure and controlled integration with external tools
- Reduced risk of unauthorised code execution
- Centralised management of AI tool access

## Governance Model

- Changes must be made via pull request (direct edits to main are restricted)
- Access to modify this repository is limited to authorised maintainers
- All updates are logged and traceable through version history

## Usage

The registry is hosted via GitHub Pages and referenced in GitHub Copilot organisational settings. Only servers listed here are available to users.

## Security Considerations

- Do not include credentials, secrets, or tokens in this repository
- All MCP servers should be reviewed for security and compliance before being added
