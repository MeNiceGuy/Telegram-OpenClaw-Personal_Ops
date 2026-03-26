# Setup Checklist

## 1. Install OpenClaw
- confirm local OpenClaw runtime is installed
- confirm agent can run locally

## 2. Configure Telegram access
- connect Telegram through the configured OpenClaw messaging path
- confirm the assistant can receive and send messages

## 3. Confirm model access
- make sure a GPT-capable model is available through the configured runtime

## 4. Add local scripts/workflows
- place your workflow scripts where the assistant/runtime can access them
- keep paths and assumptions documented

## 5. Run a simple end-to-end check
- send a Telegram request
- confirm the runtime receives it
- confirm a simple workflow completes
- confirm the result comes back through Telegram
