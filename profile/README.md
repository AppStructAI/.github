# AppStruct

Build apps visually, and work with documents, spreadsheets, presentations and social posts in the AppStruct workspace.

## Choose a starting point

| What you want to do | Start here |
| --- | --- |
| Build a web or mobile app with a visual editor | [AppStruct App Builder](https://appstruct.ai/app-builder?utm_source=github_org&utm_medium=referral&utm_campaign=github_profile_20261117&utm_content=builder) |
| Work with documents, spreadsheets, slides and social content | [AppStruct Workspace](https://appstruct.ai/workspace?utm_source=github_org&utm_medium=referral&utm_campaign=github_profile_20261117&utm_content=workspace) |
| Connect App Builder projects and data to n8n Cloud or self-hosted n8n | [AppStruct + n8n setup](https://appstruct.ai/integrations/n8n?utm_source=github_org&utm_medium=referral&utm_campaign=github_profile_20261117&utm_content=n8n_setup#n8n-cloud) |
| Connect an AI assistant to AppStruct through MCP | [MCP connection guides](https://appstruct.ai/integrations/mcp?utm_source=github_org&utm_medium=referral&utm_campaign=github_profile_20261117&utm_content=mcp_setup) |

Creating apps and using workspace products require an AppStruct account and applicable plan access.

## Maintained integrations

### n8n community nodes

[`n8n-nodes-appstruct`](https://github.com/AppStructAI/n8n-nodes-appstruct) provides App Builder project, table and record operations, plus New Row and Updated Row polling triggers.

**Verified and live on n8n Cloud**, following n8n's November 23, 2026 release notice. The instance owner/admin installs the matching AppStruct result from the canvas node panel. Self-hosted node 2.x requires n8n 2.47.7+ with Node.js 24+.

Start with the [free Cloud first-read kit](https://github.com/AppStructAI/n8n-nodes-appstruct/releases/download/v2.0.1/appstruct-n8n-cloud-first-read-kit-20261126.zip), updated November 26. Import its inactive project-list workflow, select your own credential, and compare a returned project ID and name with your AppStruct Apps library. The selected operation reads projects; the account credential itself is not restricted to reads. The kit also includes a separate inactive polling exercise and a 13-case acceptance log. No email is required to download it; connecting needs your own accounts and applicable access.

[Cloud installation and first-read walkthrough](https://appstruct.ai/integrations/n8n?utm_source=github_org&utm_medium=referral&utm_campaign=n8n_cloud_20261125&utm_content=cloud_first_read_org_01#n8n-cloud). A public entry in n8n's website directory is a separate listing; its publication has not been confirmed.

After the first read, try the [connected service-request queue review](https://blog.appstruct.ai/blog/n8n-service-request-queue-audit?utm_source=github_org&utm_medium=referral&utm_campaign=queue_audit_20261120&utm_content=live_table_digest_org_01#connect-an-appstruct-table-and-prepare-an-exception-summary): map a practice table, inspect missing owners, overdue dates and duplicate IDs, then export a CSV. The [workflow JSON and setup notes](https://github.com/AppStructAI/n8n-nodes-appstruct/blob/main/examples/SERVICE_REQUEST_REVIEW.md) are in the maintained repository. The workflow is inactive, notifications are off and its schedule is disabled; optional email contains counts only. It is an example, not an approved n8n template.

### AppStruct Social plugin

The [AppStruct Social plugin for Cursor and Claude Code](https://github.com/VladimirTambovtsev/appstruct-social-cursor-plugin) connects a compatible MCP client to Social and includes a draft-review workflow. Start with a key scoped to the intended workspace and the permissions your task needs.

MCP can save unscheduled drafts for review; it cannot schedule or publish posts. Review the channel, text and attachments in AppStruct Social before making a publishing decision. [Explore AppStruct Social](https://appstruct.ai/social?utm_source=github_org&utm_medium=referral&utm_campaign=github_profile_20261117&utm_content=social) · [Setup and first-draft guide](https://blog.appstruct.ai/blog/social-media-mcp-server).

### AppStruct Docs plugin

The [AppStruct Docs plugin for Claude Code](https://github.com/AppStructAI/appstruct-docs-claude-plugin) connects to documents you own and includes a manually invoked meeting-brief workflow. Start with a Docs key scoped to `docs:read`; the workflow drafts in the conversation and does not create or edit documents.

[Install and try the fictional meeting-notes exercise](https://blog.appstruct.ai/blog/docs-mcp-meeting-notes-to-project-brief?utm_source=github_org&utm_medium=referral&utm_campaign=docs_claude_code_20261120&utm_content=org_docs_01#use-the-optional-meeting-brief-plugin). Review the source reference, decisions, action IDs and open questions before saving a separate brief.

## Practice a database update without an account

The [database practice kit](https://github.com/AppStructAI/database-practice-kit) compares a customer-name filter, an exact saved-ID filter and an unmatched ID using two fictional requests. Run the Node.js fixture without packages or keys, then use its 16-case Supabase worksheet and three connection briefs to plan your own test.

The local exercise does not connect to a database or verify a real app. Each worksheet result starts as Not checked. The repository links to the browser example and full AppStruct connection walkthrough.

## Try one small app flow

[Build a service-request pilot](https://appstruct.ai/guides/build-service-request-app?utm_source=github_org&utm_medium=referral&utm_campaign=github_profile_20261117&utm_content=request_pilot): create a form, save fictional requests, reopen the selected record and check a status update at the published app URL. The walkthrough is a teaching example, not a customer case study.

## Help and product information

[Documentation](https://docs.appstruct.cloud/) · [Pricing](https://appstruct.ai/pricing) · [Privacy policy](https://appstruct.ai/privacy-policy)

Product and integration support: [support@appstruct.cloud](mailto:support@appstruct.cloud).
