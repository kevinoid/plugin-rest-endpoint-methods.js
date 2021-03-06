---
name: Get interaction restrictions for your public repositories
example: octokit.interactions.getRestrictionsForYourPublicRepos()
route: GET /user/interaction-limits
scope: interactions
type: API method
---

# Get interaction restrictions for your public repositories

Shows which type of GitHub user can interact with your public repositories and when the restriction expires. If there are no restrictions, you will see an empty response.

```js
octokit.interactions.getRestrictionsForYourPublicRepos();
```

## Parameters

This endpoint has no parameters

See also: [GitHub Developer Guide documentation](https://docs.github.com/rest/reference/interactions#get-interaction-restrictions-for-your-public-repositories).
