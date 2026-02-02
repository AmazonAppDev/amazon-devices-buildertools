---
name: "amazon-devices-buildertools-power"
displayName: "Amazon Devices Builder Tools"
description: "Develop applications and turbomodules on Amazon Devices OS(Vega, etc) with MCP tools and steering documents - use Amazon Devices Builder Tools(vvd, vega, kepler) and analyze performance"
keywords: ["vega", "kepler", "vvd", "react-native", "tv", "amazon", "development", "performance", "mcp"]
author: "Amazon"
---
# Amazon Devices Builder Tools

A Kiro Power for usage of Amazon Devices Builder Tools in app development that provides AI agents with essential context, tools, and guidance for building applications on Amazon Devices OS development starting with Vega OS.

## Overview

This power combines the Amazon Devices Builder Tools MCP server with curated steering documents to provide a complete development environment for Vega app development. It includes access to documentation, performance analysis tools, and architectural guidance specifically tailored for TV app development on Amazon's Vega OS.

## What's Included

### MCP Server
- **amazon-devices-buildertools-mcp**: A Model Context Protocol (MCP) server that provides context and tools for AI agents to develop and debug apps for Amazon Devices.

### Steering Documents
- **React Native for Vega Get Started Guide**: Architectural implementation guide covering project setup, dependencies, navigation, media playback, authentication, and best practices

## Key Features

### Development Tools
- Performance trace analysis with Perfetto
- KPI diagnostics (TTFF, TTFD)
- Component re-render detection
- Memory monitoring capabilities

### Architectural Guidance
- TV-optimized React Native patterns
- D-Pad navigation and focus management
- Media playback with DRM support
- Headless service implementation
- Vega-specific UI components

### Best Practices
- Performance optimization techniques
- Build and deployment workflows
- Migration from standard React Native
- Critical pitfalls to avoid

## Getting Started

Once this power is activated, you'll have access to:

1. **Documentation Tools**: Use `read_document` and `list_documents` to access Vega development guides
2. **Performance Analysis**: Use `analyze_perfetto_traces` and `get_app_hot_functions` to diagnose app performance issues
3. **Contextual Guidance**: The steering document provides AI agents with essential context for all Vega development tasks

### Tools Information

-   **CRITICAL**: For ANY question, request, or task related to Vega app development (including architecture questions, code generation, debugging, app performance, crash debugging, or general inquiries), you MUST read the relevant linked documents FIRST before answering
-   AI agents can read any .md files referenced to get correct linked document information.
-   When answering questions related to sections that have linked documents, you MUST read the linked document first before answering
-   You MUST use the `read_document` tool from `@amazon-devices/amazon-devices-buildertools-mcp` MCP server to read markdown documents linked in this document
-   If unsure which document to read, start with the architecture document to understand the context
-   If a document is not found, use `list_documents` from `@amazon-devices/amazon-devices-buildertools-mcp` to list all available documents. Optionally add a parameter to the `list_documents` from 'KB', 'PROMPT', 'STEERING', 'WORKFLOW' to narrow the search.

## Critical Note for AI Agents

-   **CRITICAL**: All Vega development questions MUST be informed by the steering document. Read the steering document by calling `read_document` tool from `@amazon-devices/amazon-devices-buildertools-mcp` MCP server with `react_native_for_vega_get_started.md` as name of the document.

## Use Cases

- Building new Vega TV applications
- Performance optimization and debugging
- Implementing TV-specific features (navigation, media, authentication)
- Following Vega development best practices

## Requirements

- Node.js and npm for running the MCP server
- Access to Vega development environment
- Understanding of React Native fundamentals

---

**Package:** :`@amazon-devices/amazon-devices-buildertools-mcp`  
**Source:** : https://www.npmjs.com/package/@amazon-devices/amazon-devices-buildertools-mcp  
**License:** : These materials are licensed as "Program Materials" under the Program Materials License Agreement (the "Agreement").  The Agreement is available at https://developer.amazon.com/support/legal/pml.  
