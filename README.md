# git_test
My first GitHub repo!  
Hello Odin!

https://www.theodinproject.com/paths/foundations/courses/foundations/lessons/setting-up-git
https://www.theodinproject.com/paths/foundations/courses/foundations/lessons/introduction-to-git
https://www.theodinproject.com/paths/foundations/courses/foundations/lessons/git-basics

## Workflows
### * Check remote storage location 
`git remote -v`

> origin	git@github.com:KwokFong/git_test.git (fetch)
> 
> origin	git@github.com:KwokFong/git_test.git (push)

- Show the URL of the repository on GitHub.
- Shows the 'remote storage' of the 'local machine' copy.
- __origin__: the connector name to the remote connection.

### * Add stuffs to staging area and commit to local branch.
`git add README.md`   
`git commit -m "<descriptions>"`

### * Push committed changes to GitHub
`git push origin main`


### * Checking status and log
`git status`

`git log`