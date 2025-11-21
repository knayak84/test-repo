# test-repo
This repo is for testing some concepts of github merges. ff merge, regular merge and squash merge.
This is first commit.
First PR - With sqaush commit to dev and then to main.
First PR - With sqaush commit to dev and then to main - second commit.
Second PR - with normal commit.
Third PR - with normal merge(with only `Allow merge commits` enabled in the github settings. The `Allow squash merging` and `Allow rebase merging` is disabled for this repo).
4th PR - to test with the linear commit history settings.
5th PR - As the linear commit history is good thing to have.The problem is because it uses the Gitflow strategy, the sqash merge is creating issue. So once we go to the Github flow, this gets resolved. So we should be able to have both the squash merge and linear history. So for now, if we enable the regular merge(merge commits), this causes issue in maintaining the linear history. So creating the workflow to merge the PR on approval using the fast forward merge. This should resolve the issue with the squash merge when maintaing two branches like dev and main.
