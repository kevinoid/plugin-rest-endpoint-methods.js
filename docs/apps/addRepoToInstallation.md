---
name: Add a repository to an app installation
example: octokit.apps.addRepoToInstallation({ installation_id, repository_id })
route: PUT /user/installations/{installation_id}/repositories/{repository_id}
scope: apps
type: API method
---

# Add a repository to an app installation

Add a single repository to an installation. The authenticated user must have admin access to the repository.

You must use a personal access token (which you can create via the [command line](https://help.github.com/articles/creating-a-personal-access-token-for-the-command-line/) or the [OAuth Authorizations API](https://docs.github.com/rest/reference/oauth-authorizations#create-a-new-authorization) or [Basic Authentication](https://docs.github.com/rest/overview/other-authentication-methods#basic-authentication) to access this endpoint.

```js
octokit.apps.addRepoToInstallation({
  installation_id,
  repository_id,
});
```

## Parameters

<table>
  <thead>
    <tr>
      <th>name</th>
      <th>required</th>
      <th>description</th>
    </tr>
  </thead>
  <tbody>
    <tr><td>installation_id</td><td>yes</td><td>

installation_id parameter

</td></tr>
<tr><td>repository_id</td><td>yes</td><td>

</td></tr>
  </tbody>
</table>

See also: [GitHub Developer Guide documentation](https://docs.github.com/rest/reference/apps#add-a-repository-to-an-app-installation).
