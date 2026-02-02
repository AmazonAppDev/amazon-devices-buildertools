# Amazon Devices Builder Tools

This repo is intended to host Amazon Devices Builder Tools to be distributed on GitHub.

## Available Tools

- **Amazon Devices Builder Tools Power**: A Kiro Power for Amazon Devices OS development starting with Vega OS.

## Amazon Devices Builder Tools Power

A Kiro Power for usage of Amazon Devices Builder Tools in app development that provides AI agents with essential context, tools, and guidance for building applications on Amazon Devices OS development starting with Vega OS.

### What is a Kiro Power?

A Kiro Power packages documentation, workflow guides, and MCP servers to extend Kiro's capabilities. Learn more at [kiro.dev/powers](https://kiro.dev/powers/).

### Installation

This power can be installed in Kiro IDE through the Powers management panel or by adding it to your workspace configuration. Learn more at [Install Custom Powers](https://kiro.dev/docs/powers/installation/#install-custom-powers)

### Power Components

#### MCP Server
- **amazon-devices-buildertools-mcp**: Provides tools for reading Vega documentation, analyzing performance traces, and accessing development guidance
  - Package: `@amazon-devices/amazon-devices-buildertools-mcp`
  - Source: https://www.npmjs.com/package/@amazon-devices/amazon-devices-buildertools-mcp

### Development

To modify this power:

1. Update `POWER.md` for power metadata and documentation
2. Update `mcp.json` for MCP server configuration

### Test

Follow the instructions in [Install Kiro Powers from Local Path](https://kiro.dev/docs/powers/installation/#from-local-path) to install the modified power with Kiro IDE.