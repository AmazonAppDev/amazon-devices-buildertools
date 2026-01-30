# Amazon Devices Builder Tools Kiro Power

This repository contains a [Kiro Power](https://kiro.dev/powers/) for Amazon Devices Builder Tools.

## What is a Kiro Power?

A Kiro Power package documentation, workflow guides, and MCP servers to extend Kiro's capabilities. Learn more at [kiro.dev/powers](https://kiro.dev/powers/).

## Installation

This power can be installed in Kiro through the Powers management panel or by adding it to your workspace configuration.

## Power Components

### MCP Server
- **amazon-devices-buildertools-mcp**: Provides tools for reading Vega documentation, analyzing performance traces, and accessing development guidance
  - Package: `@amazon-devices/amazon-devices-buildertools-mcp`
  - Source: https://www.npmjs.com/package/@amazon-devices/amazon-devices-buildertools-mcp

### Steering Documents
- **React Native for Vega Get Started Guide**: Comprehensive architectural implementation guide

## Development

To modify this power:

1. Update `POWER.md` for power metadata and documentation
2. Update `mcp.json` for MCP server configuration
3. Add or modify steering documents in the `steering/` directory
