# Setup Notes

This project is environment-specific. A working version requires:

- OpenClaw installed and configured locally
- a messaging integration such as Telegram configured through the runtime
- access to a GPT-capable model through the configured OpenClaw setup
- local scripts/tools for the workflows you want the system to handle

## Key idea
This is not just a chatbot setup. The value comes from connecting:
- remote messaging
- agent reasoning
- local execution
- structured workflows

## What to adapt
Anyone building a similar system would need to adapt:
- messaging setup
- local tool paths
- file locations
- scripts and workflow logic
- safety boundaries and permissions
