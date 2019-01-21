# Quality

本文档主要是描述我对于团队前端项目的一些质量把控措施。

## Authors

@bqliu

## 方案

See [diagram](https://www.processon.com/diagraming/5c3bee64e4b0fa03ce97b1fd).

dev          ==> pre-release  ==> release
----             ----             ----
lint             自测（e2e）       log 
test                              bug-review
ci
code-review
svn/git control

code review 和 bug review 结果对比
  - 用来评判 code review 和 自测 的质量
- --------------------------------------
bug review
- --------------------------------------
release log
- --------------------------------------
ui test（自测）
- --------------------------------------
code reivew
- --------------------------------------
ci/cd
- --------------------------------------
unit test/e2e test
  - jest
  - chromedriver
- --------------------------------------
svn/git control
  - svn: hooks + logtemplate
  - git: hooks(husky + commitizen)
  - refs
    - [template](https://jingyan.baidu.com/article/e5c39bf5ed822d39d6603378.html)
    - [git-cz](https://github.com/commitizen/cz-cli)
- --------------------------------------
linter(code/log)
  - eslint
  - stylelint
  - htmllint
  - refs
    - [eslint](https://eslint.org/)
    - [stylelint](https://stylelint.io/)
    - [htmllint](https://github.com/htmllint/htmllint)
- --------------------------------------
