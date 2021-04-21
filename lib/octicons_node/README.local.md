# @primer/octicons


## 构建

1. 在根目录安装依赖，构建一次
2. 进到node，安装依赖，构建 `yarn build`
3. 构建es模块，构建`yarn build:es`


## 保持上游同步

```sh
$ git fetch upstream

$ git checkout main

$ git rebase upstream/main

$ git checkout <local-branch>

$ git rebase main
```

本地分支修改后，上游分支有更新，需要将更新拉取下来，反映在本地分支，
本地分支的修改要保留