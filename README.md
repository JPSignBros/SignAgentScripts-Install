# Sign Brothers SignAgent Scripts — Install / Update

Use this page to install or refresh the approved Sign Brothers Tampermonkey tools for SignAgent.

## Before you begin

1. Install and enable [Tampermonkey from the Chrome Web Store](https://chromewebstore.google.com/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo).
2. Open each **Install / Update** link below in Chrome.
3. Tampermonkey will open a confirmation screen. Choose **Install** or **Update**.
4. Refresh SignAgent after installing both tools.

> Tampermonkey requires a separate confirmation for each independent userscript. This repository page is the single company-shareable starting link.

## Approved production tools

### 1. Batch Place + Friendly Names

[Install / Update SignAgent Batch Place + Friendly Names](https://github.com/JPSignBros/SignAgentScripts-Install/raw/refs/heads/main/SignAgentBatchPlaceFriendlyNames.user.js)

Queues multiple sign placements while preserving facing direction, then shows readable Project, Location, Sign Type, and State labels in the Batch Place details and Save All confirmation.

- Production version: `1.0.0`
- Includes the frozen Batch Place + Direction Drag baseline automatically.
- Do **not** also enable the standalone historical `SignAgentBatchPlace.user.js` file.

### 2. Resizable Sidebar

[Install / Update SignAgent Resizable Sidebar](https://github.com/JPSignBros/SignAgentScripts-Install/raw/refs/heads/main/SignAgentSidebarWidth.user.js)

Makes the Projects / Locations / Sign Types sidebar resizable and remembers the selected width on that computer.

- Production version: `1.0.0`
- Makes no SignAgent API calls and does not change project data.

## Support and update behavior

- These scripts run only on `https://app.signagent.com/*`.
- Future approved versions can be detected through their public Tampermonkey update metadata.
- Development builds, test branches, and unfinished tools are maintained privately and are not employee installers.
- If a tool appears disabled after installation, confirm Tampermonkey is enabled and refresh the SignAgent tab.

## Historical dependency

`SignAgentBatchPlace.user.js` is the frozen Batch Place v1.0.0 baseline imported from Tyler Sedacca's known-good source. It remains public because the approved Friendly Names wrapper loads its immutable import commit. It is not a separate employee installation.
