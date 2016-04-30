This is a good site to figure out what is Git and Github (Read this first if you have not used Git and Github):

[Click me](https://www.atlassian.com/git/tutorials/what-is-version-control/) 

## Setup

Fork https://github.com/BitTigerInst/MiniAppStore.git

Clone your Fork (i.e. if your user-id is foo, `git clone git@github.com:foo/MiniAppStore.git`)

`git remote add miniAppStore git@github.com:BitTigerInst/MiniAppStore.git`

## Coding
`git pull miniAppStore master`
// Do your work

`git add (all your files)`
// Finished work

`git commit -m "* Homework x submission"`
// Push to your own fork

`git push`
// then open a Pull Request at https://github.com/BitTigerInst/MiniAppStore.git

After your open a pull request, I(along with other members) will review the code and do the merging.

## Troubleshooting
If you're having a permission denied issue, you may need to setup SSH keys first; read this
https://help.github.com/articles/error-permission-denied-publickey/


Other helpful git commands:

`git log`// to see all commits you've done

`git rm`// instead of adding a file, if you need to remove a file
