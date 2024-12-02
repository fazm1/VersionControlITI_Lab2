● Tell me how to remove them locally and remotely.
To remove them locally, we can use command: git reset --soft HEAD^^
then to remove remotely, we can just push using the command: git push origin master


● Tell me how to checkout another branch without commit
changes 
Simply use the command "git checkout (branch name)", before commiting.
Or you can undo last commit using the command "git restore --staged", then switch branch using "git checkout (branch name)"

● Tell me how to list tags.
git tag

● Tell me how to delete tag locally and remotely.
git tag -d (tag_name)

● Add an image in the README.md file.
![Pasted image](https://github.com/user-attachments/assets/53af7db0-2b58-4264-9a4c-44a204a51830)
