## Toolset

- [oh-my-zsh](http://ohmyz.sh/)
- [Sublime Text](https://www.sublimetext.com/)
- [git](https://git-scm.com/)
- Ruby via [`rbenv`](https://github.com/rbenv/rbenv)

## VSCode 

- Check https://gist.github.com/ to sync.
- If conflict with sublime:

```
git config --global core.editor "code --wait"
git config --global -e
``` 

and in `gitconfig`
```
[diff]
    tool = default-difftool
[difftool "default-difftool"]
    cmd = code --wait --diff $LOCAL $REMOTE
```

