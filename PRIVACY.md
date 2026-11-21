# H-Code Browser Extension Privacy Policy

Effective date: 21 November 2026

This policy describes how the H-Code browser extension handles information when you use it on chatgpt.com or claude.ai. The extension is maintained by [sredocevitaerc](https://github.com/sredocevitaerc).

## Information used

H-Code reads project and conversation metadata from the ChatGPT or Claude account already signed in within your browser. This includes project and conversation names, identifiers, links, project membership, and activity dates used to build and order the sidebar. When renaming a ChatGPT project, it reads that project's existing settings so it can preserve them in the update. H-Code does not intentionally read or save conversation message bodies.

The extension reads the current page URL and visible conversation titles to identify and highlight the open item. On Claude, it may read the last active organization cookie to choose the correct account organization. It uses the browser's existing signed-in session for account requests. If ChatGPT requires an access token for a request, the extension keeps it in memory only while the page is running; it does not save the token in browser storage.

## Local storage and retention

H-Code stores its sidebar data in your browser's extension local storage, separately for ChatGPT and Claude. This includes imported project and conversation metadata, local folder placement, and interface choices such as expanded sections, panel size and position, and scroll position. This data remains in your browser profile until you clear the extension's data or uninstall it. Clearing local data does not undo project or conversation changes already made in your ChatGPT or Claude account.

## Account requests and sharing

H-Code sends requests directly from your browser to chatgpt.com or claude.ai to sync projects and conversations and to perform actions you choose, such as creating or renaming a project, moving a conversation, or deleting a project or conversation. Those services process the requests under their own terms and privacy policies. H-Code does not send account data to a developer server, analytics service, or advertising network. It does not sell user data.

If you submit a bug report to this public GitHub repository, the information you choose to include is public and is handled by GitHub under GitHub's policies. Do not post conversation content, account identifiers, credentials, or tokens in public issues.

## Permissions

The extension requests browser storage access to remember its sidebar data and access to chatgpt.com and claude.ai so it can display the sidebar and make account requests on those sites. It does not request access to unrelated websites.

## Your choices

You can close the H-Code sidebar, disable or uninstall the extension, and clear its stored data through your browser. You can manage or delete projects and conversations in ChatGPT or Claude. Account data held by those services is governed by their respective policies.

## Changes and contact

We may update this policy when the extension's behavior changes. The current version will be published here with its effective date. For policy questions, use the [issue tracker](https://github.com/sredocevitaerc/H-Code-Browser-Issues/issues) without including private account data. For a private matter, use the contact information on the [maintainer's GitHub profile](https://github.com/sredocevitaerc).
