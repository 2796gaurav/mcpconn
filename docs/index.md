<iframe width="560" height="315" src="https://www.youtube.com/embed/Xzni71r0A_M?si=V2AJ5cqL8_dWE6Vs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

![mcpconn logo](images/logo.png)

# Welcome to mcpconn

**mcpconn** is a Python library that provides a simple and efficient way to connect your applications to AI models using the Model Context Protocol (MCP). It acts as a wrapper around the `mcp` library, offering a streamlined client interface for seamless integration with various AI providers and transport protocols.

[![PyPI version](https://badge.fury.io/py/mcpconn.svg)](https://badge.fury.io/py/mcpconn)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## ✨ Features

- **Simplified Client Interface**: A high-level `mcpconn` for easy interaction with MCP servers.
- **Multi-provider Support**: Out-of-the-box support for Anthropic and OpenAI models.
- **Flexible Transports**: Connect to servers using STDIO, SSE, or Streamable HTTP.
- **Built-in Guardrails**: Protect your application with content filtering, PII masking, and injection detection.
- **Conversation Management**: Easily manage conversation history, context, and persistence.
- **Asynchronous by Design**: Built with `asyncio` for high-performance, non-blocking I/O.
- **Extensible**: Easily add new LLM providers, transports, or guardrails.

Ready to dive in? Check out the [Getting Started](getting-started.md) guide. 