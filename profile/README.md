# AppStruct

Build apps visually, and work with documents, spreadsheets, presentations and social posts in the AppStruct workspace.

## Choose a starting point

| What you want to do | Start here |
| --- | --- |
| Build a web or mobile app with a visual editor | [AppStruct App Builder](https://appstruct.ai/app-builder?utm_source=github_org&utm_medium=referral&utm_campaign=github_profile_20261117&utm_content=builder) |
| Work with documents, spreadsheets, slides and social content | [AppStruct Workspace](https://appstruct.ai/workspace?utm_source=github_org&utm_medium=referral&utm_campaign=github_profile_20261117&utm_content=workspace) |
| Connect App Builder projects and data to a self-hosted n8n workflow | [AppStruct + n8n setup](https://appstruct.ai/integrations/n8n?utm_source=github_org&utm_medium=referral&utm_campaign=github_profile_20261117&utm_content=n8n_setup) |
| Connect an AI assistant to AppStruct through MCP | [MCP connection guides](https://appstruct.ai/integrations/mcp?utm_source=github_org&utm_medium=referral&utm_campaign=github_profile_20261117&utm_content=mcp_setup) |

Creating apps and using workspace products require an AppStruct account and applicable plan access.

## Maintained integrations

### n8n community nodes

[`n8n-nodes-appstruct`](https://github.com/AppStructAI/n8n-nodes-appstruct) provides App Builder project, table and record operations, plus New Row and Updated Row polling triggers.

For self-hosted n8n 2.47.7+ with Node.js 24+. Start with the included inactive, read-only project-list workflow, select your own credential, and compare a returned project ID and name with your AppStruct Apps library. Then test polling against fictional records before adding a destination. Installation and compatibility details are in the repository README.

### AppStruct Social plugin

The [AppStruct Social plugin for Cursor and Claude Code](https://github.com/VladimirTambovtsev/appstruct-social-cursor-plugin) connects a compatible MCP client to Social and includes a draft-review workflow. Start with a key scoped to the intended workspace and the permissions your task needs.

MCP can save unscheduled drafts for review; it cannot schedule or publish posts. Review the channel, text and attachments in AppStruct Social before making a publishing decision. [Read the setup and first-draft guide](https://blog.appstruct.ai/blog/social-media-mcp-server?utm_source=github_org&utm_medium=referral&utm_campaign=github_profile_20261117&utm_content=social_guide).

## Try one small app flow

[Build a service-request pilot](https://appstruct.ai/guides/build-service-request-app?utm_source=github_org&utm_medium=referral&utm_campaign=github_profile_20261117&utm_content=request_pilot): create a form, save fictional requests, reopen the selected record and check a status update at the published app URL. The walkthrough is a teaching example, not a customer case study.

## Help and product information

[Documentation](https://docs.appstruct.cloud/) · [Pricing](https://appstruct.ai/pricing) · [Privacy policy](https://appstruct.ai/privacy-policy)

Product and integration support: [support@appstruct.cloud](mailto:support@appstruct.cloud).
