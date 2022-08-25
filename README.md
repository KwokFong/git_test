# git_test

https://www.theodinproject.com/paths/foundations/courses/foundations/lessons/setting-up-git
https://www.theodinproject.com/paths/foundations/courses/foundations/lessons/introduction-to-git
https://www.theodinproject.com/paths/foundations/courses/foundations/lessons/git-basics

## __Workflows__
### * Check remote storage location.
`git remote -v`

    origin	git@github.com:KwokFong/git_test.git (fetch)
    origin	git@github.com:KwokFong/git_test.git (push)

- Show the URL of the __remote__ repository on GitHub.
- Shows the __remote storage__ of the 'local machine' copy.
- __origin__: the connector name to access the remote location.

### * Add stuffs to __staging__ area and commit to __local__ branch.
`git add README.md`   
`git commit -m "<descriptions>"`

### * Push committed changes (from local) to GitHub (remote).
`git push origin main`


### * Checking status and log
`git status`  
`git log`