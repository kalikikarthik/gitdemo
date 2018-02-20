# gitdemo


#branch 

git checkout -b name 
#create
git tag v1

#list tag

git tag

-------------------------
1 checking existing tags

$ git tag
2 create a signed tag (for push to a remote repository such as github)

$ git tag -a v0.1
3 push tags to your remote repository (check "git remote")

$ git push --tags
4 delete your tags locally

$ git tag -d v0.1
5 delete tag on remote repository

$ git push origin :v0.1
---------------------------------------
