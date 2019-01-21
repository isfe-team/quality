# Project Quality Monitor

 主要是项目从开发到预发布最后到发布整个过程中的质量管理

## Develop

1. `Lint` 

	- `eslint` [官网](https://eslint.org/)
	- `stylelint` css检查工具 [官网](https://stylelint.io/)
	- `commitlint` [官网](http://marionebl.github.io/commitlint/#/)
	- `htmllint` [官网](https://github.com/htmllint/htmllint)

2. `Test`

	- `unit-test`
	- `e2e-test`

3. `Svn/Git control`
 
	- `commit-message control`： 配置不同操作对应的提交日志模版，控制项目提交记录信息一致性
	- `commit hooks`: 提交的一些钩子
	- `code review`：code review 可以在每次提交时，审查修改的内容，是否有误修改部分，在更新时也可查看成员的提交记录。
	- `CI/CD`
	svn的`commit control`手动配置了

## Rre-Release

1. `unit-test`

2. `e2e-test`

## Release

1. `release-log`

2. `bug-review`

3. 周期性的bug分析



