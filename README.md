## ReadMe

This is created in GitLab and should mirror over to GitHub via ssh easily. edit: It does, yay!

---

[Push mirroring](https://docs.gitlab.com/ee/user/project/repository/mirror/) is setup on the GitLab side, targeting `ssh://git@github.com/TheKolega/mirror-test-github.git` and using SSH auth.
This creates an public SSH key which can pe copied over to GitHub either as a global SSH key for that user or a deployment key on a specific repo.

Optionally, fine-grained PATs can also be used with the Password authentication method.
