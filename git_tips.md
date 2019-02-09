# git tricks & links

### [removing large files wrongly comitted](http://thomas-cokelaer.info/blog/2018/02/git-how-to-remove-a-big-file-wrongly-committed/)
- `git filter-branch --tree-filter 'rm -rf path/to/your/file' HEAD`

### [how to make git show tracked directories](https://stackoverflow.com/questions/20247389/how-can-i-make-git-list-only-the-tracked-directories-in-a-folder)
- `git ls-files | xargs -n 1 dirname | uniq`
- `git ls-tree -r master --name-only` [list of files that are being tracked](https://stackoverflow.com/questions/15606955/how-can-i-make-git-show-a-list-of-the-files-that-are-being-tracked/15606998)
### Git push
- [Git Doc - push](https://help.github.com/articles/pushing-to-a-remote/) `git push  <REMOTENAME> <BRANCHNAME>`
- [Force “git push” to overwrite remote files](https://stackoverflow.com/questions/10510462/force-git-push-to-overwrite-remote-files)
### Git ignore
- Ignore all directories `*/` in .gitignore

### list git repos
- `find / -name ".git"` on linux
- `find / -name ".git" | grep /path/to/home_dir/`

### html -> ssh
- [Changing a remote's URL - official doc](https://help.github.com/articles/changing-a-remote-s-url/)

