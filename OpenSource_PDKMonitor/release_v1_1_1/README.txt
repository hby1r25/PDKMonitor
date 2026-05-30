CORNERSTONE PDK Monitor v1.1.1
===============================
Single-file browser dashboard for silicon photonics PDK management.
Designed by Emre Kaplan · pdk.cornerstone.soton.ac.uk
Licence: TAPR Open Hardware Licence v1.0

CONTENTS
--------
  cornerstone-pdk-monitor-v1.1.1.html   — Main dashboard (open in any modern browser)
  dashboard.json                        — Default pre-populated PDK dataset
  USER_MANUAL.md / .docx / .pdf         — Full user manual
  CHANGELOG.md                          — Release notes
  README.txt                            — This file

HOW TO USE
----------
1. Open cornerstone-pdk-monitor-v1.1.1.html in Chrome, Firefox, or Safari.
2. No server or installation required — works fully offline.
3. On first launch: accept the licence terms.
4. The dashboard loads pre-populated with CORNERSTONE BBs.
5. Import dashboard.json via the Import button to reset to defaults.
6. See USER_MANUAL for the full guide.

WHAT'S NEW IN v1.1.1
--------------------
- Sign-in rate limit relaxed: now 5 failed attempts per identity per
  1 hour (was 3 per 24 hours). The 3-second cooldown between submits
  and the 60-second "Request access" cooldown are unchanged.
- Manage Lists → "Fetch & merge user lists" now works for user-admins
  (previously full Admin only) and adds a one-click 🔀 "Merge from
  ALL sources" path that folds every users/<name>/dashboard.json slice
  into the main lists in one shot. Original ownership and labels are
  preserved across the merge so the "added by X" badge survives.
- User-admins can publish their slice with custom statuses, categories,
  BB types, EDA tools, CDI axes, layers, platforms, benchmark metrics
  and sketch library entries, and Admin can pull them all in safely
  without overwriting admin-owned items.

AI AGENT QUICK START
--------------------
1. Click 🧠 Insight in the header.
2. Choose ⚙ Configure — enter your Anthropic/OpenAI API key.
3. Click 💬 Chat with the agent to start.
4. In the chat, click ▶ Data files in context to load CSV/JSON files
   from GitHub for analysis (🔬 Analyse files with AI).
5. Click ⧉ Detach to pop the chat into a floating window.

LINKS
-----
Open Platform GitHub : https://github.com/cornerstone-uos/cornerstone-community
Main PDK GitHub      : https://github.com/cornerstone-uos/cornerstone-pdk
Website              : https://cornerstone.sotonfab.co.uk
