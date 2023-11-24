# Release Notes

### New Features 🎉

- 基础框架设计

### Bug Fixes 🐞

### Other Improvements 👀

## v0.1.0 (2021-01-01)

### New Features 🎉

- version 版本规则
    - `v`：版本号前缀
    - `0`：大版本号，表示不同的业务模块
    - `1`：小版本号，表示不同的功能模块
    - `0`：修订号，表示 bug 修复或者是性能优化
- branch 分支规则
    - `master`：主分支，用于发布稳定版本
    - `develop`：开发分支，用于开发新功能
    - `feature`：功能分支，用于开发新功能
    - `release`：发布分支，用于发布新版本
        - `release/v0.1`：只体现到小版本号，具体的修订号在标签中体现
    - `hotfix`：修复分支，用于修复 bug
- tag 标签规则
    - `v0.1.0`：版本号
    - `v0.1.0-alpha.1`：预发布版本号
    - `v0.1.0-beta.1`：测试版本号
    - `v0.1.0-rc.1`：候选版本号


