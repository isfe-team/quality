# Git

基于以下开源工具：

- [husky](https://github.com/typicode/husky)
- [commitizen](https://github.com/commitizen/cz-cli)
- [commitlint](https://github.com/marionebl/commitlint)

## Sample

```json
// package.json
{
  "scripts": {
    // run this initial
    "commit:prev": "commitizen init cz-conventional-changelog --save --save-exact --force",
    "commit": "git-cz"
  },
  "husky": {
    "hooks": {
      "pre-commit": "npm run lint",
      "commit-message": "commitlint -E $HUSKY_GIT_PARAMS"
    }
  },
  "devDependencies": {
    "@commitlint/cli": "^7.3.2",
    "@commitlint/config-conventional": "^7.3.1",
    "commitizen": "^3.0.5",
    "husky": "^1.2.1"
  }
}
```
