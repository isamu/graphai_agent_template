# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

Template repository for creating GraphAI agents. Provides boilerplate code and project structure for developing custom agents compatible with the GraphAI framework.

## Commands

```bash
yarn build      # Compile TypeScript (tsc && tsc-alias)
yarn lint       # Run ESLint
yarn format     # Format with Prettier
yarn test       # Run tests (node:test with ts-node)
```

## Architecture

- `src/` - Agent source code (sample_agent.ts as reference)
- `tests/` - Test files (test_*.ts pattern)
- Uses TypeScript with tsc-alias for path resolution
- ESLint flat config (eslint.config.mjs)
