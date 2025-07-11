## Get Started (30 seconds)

```bash
git clone --recursive git@github.com:keyboard-dev/keyboard-local.git
cd keyboard-local

# Work on desktop app
cd apps/approver-client
npm install && npm run build


# Work on server (different terminal)
cd apps/keyboard-mcp
npm install && npm run dev
```

Read the docs to fully get started.

## 🔥 Important: How to Contribute
✅ DO THIS:

Make changes in apps/approver-client/ or apps/keyboard-mcp/
Create branches and commits like normal
Submit PRs to the individual repos:

Approver Client changes → https://github.com/keyboard-dev/approver-client

Keyboard MCP changes → https://github.com/keyboard-dev/keyboard-mcp



## ❌ DON'T DO THIS:

Don't submit PRs to this monorepo (unless changing this README)
Don't worry about "updating submodules" - handled automatically

That's It!
Work like you normally would. This repo just saves you from cloning multiple repositories.
