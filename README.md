# FoxCut

Official Cursor / Agent plugin for [FoxCut](https://foxcut.ai), a directable AI video and image studio.

Connects an agent to FoxCut over MCP so it can inspect the model catalog, estimate credit costs, generate or edit images and video, create talking avatars and reusable characters, poll jobs, and retrieve private outputs.

MCP endpoint: `https://mcp.foxcut.ai/mcp`

Install opens FoxCut’s OAuth consent screen. No API key is pasted into the plugin. Read-only planning and estimates do not spend credits. Creation tools are billed to the connected FoxCut account; the agent should show the estimate and obtain confirmation first.

## Try it

- “Show my FoxCut plan and credit balance.”
- “Recommend a model for a five-second vertical product clip and estimate the cost.”
- “Create three product-photo concepts from this image, but ask before spending credits.”
- “List my recent generations and tell me which are ready.”

## Local check

Copy or symlink this directory to `~/.cursor/plugins/local/foxcut`, then reload Cursor and confirm FoxCut appears under Customize.

Support: https://foxcut.ai/support  
Privacy: https://foxcut.ai/privacy  
Terms: https://foxcut.ai/terms
