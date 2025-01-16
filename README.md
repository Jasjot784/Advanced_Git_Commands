# Advanced_Git_Commands

1. git config --global user.name "user name"
2. git config --global user.email "email "
3. git config --list
4. git log
5. git log -p  // every commit changes
6. git show 078.. //that particular commit
7. git log graph // tells about branches
8. git log --grep = 'example' // commit messages nearby relation
9. git log --oneline
10. git clean -f // removes all uncommited files
11. git reset // change staged changes to working directory
12. git config credential.username "Jasjot" //changes name
13. git reset --soft HEAD~1 // revoke 1 commit, changes will be there in working directory commit will be gone
14. git reset --hard HEAD~1 // remove changes also
15. git reflog // what all happens to local repo
16. git bisect // uses binary search and tells which commit has issue
17. git bisect star, git bisect good, git bisect bad
18. git tag <tag_name>
