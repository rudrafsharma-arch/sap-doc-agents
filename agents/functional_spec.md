# Functional Spec Agent

This agent is called by the SAP Document Builder via Claude Code CLI.

## Purpose
Generates Functional Specification (FS) documents

## How it works
1. MCP Server receives document generation request from the React app
2. MCP Server calls Claude Code CLI with the agent prompt
3. Claude Code uses your subscription to generate the document
4. Generated HTML document is returned to the browser

## Agent Definition
See mcp-server/server.js for the full system prompt used by this agent.
