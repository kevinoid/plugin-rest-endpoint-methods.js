---
name: Get a branch
example: octokit.repos.getBranch({ owner, repo, branch })
route: GET /repos/{owner}/{repo}/branches/{branch}
scope: repos
type: API method
---

# Get a branch

```js
octokit.repos.getBranch({
  owner,
  repo,
  branch,
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
    <tr><td>owner</td><td>yes</td><td>

</td></tr>
<tr><td>repo</td><td>yes</td><td>

</td></tr>
<tr><td>branch</td><td>yes</td><td>

branch+ parameter

</td></tr>
  </tbody>
</table>

See also: [GitHub Developer Guide documentation](https://docs.github.com/rest/reference/repos#get-a-branch).
