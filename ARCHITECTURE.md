# Architecture

## Core components

### 1. Telegram
Acts as the remote interface for sending commands, requests, and tasks.

### 2. OpenClaw
Acts as the local agent runtime and orchestration layer.

### 3. GPT-powered reasoning
Handles interpretation, planning, summarization, and task shaping.

### 4. Local scripts and tools
Carry out machine-side workflows such as:
- file operations
- automation scripts
- workflow scaffolding
- content preparation
- business audit setup

## Example flow
1. User sends a request through Telegram.
2. OpenClaw receives and routes the request.
3. GPT-powered reasoning interprets the task.
4. Local scripts, tools, or workflows are used when appropriate.
5. Results are returned through Telegram.

## Design emphasis
- practical execution
- local usefulness
- remote convenience
- modular workflows
- agent-assisted operations instead of passive chat
