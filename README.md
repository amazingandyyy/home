# Home

This repository contains configuration files that I don't want to have to lose
so I'm putting them under version control.

## Breadcrumbs

### Git

Adding a subtree project:

```
git remote add -f vim-projectroot git@github.com:dbakker/vim-projectroot.git
git subtree add --prefix .vim/bundle/vim-projectroot vim-projectroot master --squash
```

- [Git subtree merge](https://help.github.com/articles/about-git-subtree-merges/)
- [Alternatives to git submodule](https://blogs.atlassian.com/2013/05/alternatives-to-git-submodule-git-subtree/)


### Vim

- [ProjectRoot](https://github.com/dbakker/vim-projectroot) - Handy switching
  the current working directory
- [CtrlP](https://github.com/ctrlpvim/ctrlp.vim) - Easily open files within the
  current project
- [Pathogen](https://github.com/tpope/vim-pathogen) - We would add this as a
  subtree but it conflicts with the existing .vim path
  - [src](https://raw.githubusercontent.com/tpope/vim-pathogen/master/autoload/pathogen.vim) -
    To be used with `curl [src] > .vim/autoload/pathogen.vim`.
 

