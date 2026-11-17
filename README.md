# .github

Organization defaults for secondshift-labs.

`workflow-templates/ai-review.yml` adds AI review to a repository in one click: open the repository's **Actions** tab, choose **New workflow**, and pick **AI review** under this organization. The comment at the top of the file lists the secret and the two variables to set before the first round.

A repository gets a copy of the template, pinned to one `ai-review-workflows` release commit. Later releases reach that copy only through Dependabot, and only where the repository enables Dependabot's `github-actions` updates. Changing this template does not update existing copies.
