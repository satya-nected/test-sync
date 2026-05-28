# Nected Workspace Sync

This repository is connected to a [Nected](https://www.nected.ai) workspace and stores its **Rules, Workflows, Datasets, Connectors, Tags, and Variables** as version-controlled JSON.

Each commit on this repo represents a snapshot of the workspace, pushed from Nected when authors save or publish entities. Branches map to Nected environments — use them to collaborate, review, and promote changes safely.

> ⚠️ Do not hand-edit files in this repo. All changes should be authored in the Nected UI; manual edits will be overwritten on the next sync.

## Folder layout

| Folder | Contents |
|---|---|
| `rule/` | Decision tables, rule chains, simple rules |
| `workflow/` | Multi-step orchestrations |
| `dataSet/` | Reference data tables |
| `connector/` | External integrations (DB, API, webhooks) |
| `tag/` | Labels for organizing entities |
| `variable/` | System and global variables |

Each entity lives in a UUID-named subfolder containing `draft.json` (working copy) and one `<version>.json` file per published version.

## Documentation

- **Git-based Source Control overview:** https://docs.nected.ai/nected-docs/development-lifecycle/git-based-source-control
- **Nected docs home:** https://docs.nected.ai
- **Platform login:** https://app.nected.ai

## 🤝 Community & Support

For questions, feedback, or contributions:

- Visit our **[documentation](https://docs.nected.ai/)**
- Join the conversation on **[LinkedIn](https://www.linkedin.com/company/nected-ai/)**
- Contact the team via **[support@nected.ai](mailto:support@nected.ai)**
