---
name: business-setup
description: The setup interview that builds a real estate agent's business hub, and the check that tunes up the whole hub. Use this whenever the agent says "set up my business", "start my setup", "run setup", "finish my setup", "check my setup", "check my files", "check my hub", "tune up my hub", "what is missing in my hub", "add [town] to my areas", or anything close to those, and whenever the agent wants to build, resume, add to, or check the business files in their hub folder (My Brand, My Voice, My Clients, My Goals, Start Here) or anything in the hub. Also use it when the agent re-runs setup after finishing, or wants their business constitution regenerated.
---

# AGNTRX, business-setup

When the agent asks to check their hub, their setup, or their files, start with agntrx_status. Before anything else, and whether or not a hub folder is connected, show these two lines exactly:
"AGNTRX is on for your account."
"Plugin 1.0.1. Home base [the home base number from its answer]."
The plugin number and the home base number are counted separately and never match; a different number is not a problem. Only if its answer names a newest plugin above 1.0.1, add: "Your AGNTRX plugin needs a quick update. Your office has the new file." Then ask AGNTRX for this helper's instructions as below.

This helper's instructions live on the AGNTRX home base, not in this file.

1. Ask AGNTRX for this helper's instructions with the tool named below, and follow what comes back.
2. If no AGNTRX tool is in this chat, say exactly this and stop:
   "AGNTRX isn't connected yet. Open the plugin's Connectors tab, click connect, and sign in."
3. If the AGNTRX tool fails or gives back nothing, try once more. If it fails again, say exactly this and stop:
   "AGNTRX can't reach its home base right now. Your files are safe on your computer. Try again in a few minutes."
4. If AGNTRX answers with a message about access or terms instead of instructions, say that message word for word, add nothing, and stop.
5. Without instructions from AGNTRX, never build, rebuild, or guess any part of this helper's work from memory or from another skill. You may help the agent open and read their own files. Never say why access ended.

Tool: agntrx_open, with helper "business-setup".

Copyright 2026 The Scalable Agent. All rights reserved.
