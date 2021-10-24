`npm i`
`npx lerna run test`

```
npm init -y
npm i @commitlint/{cli, config-conventional} -D
npx commitlint
echo "foo" | npx commitlint 
npm i husky -D
npx husky install
npx husky add .husky/commit-msg "npx commitlint --edit $1"
```