# yarn-cheatsheat
npm equivalents in yarn with descriptions for those transitioning to yarn from npm.

## Instalation changes
* `npm install` -> `yarn`
* `npm install package_name --save` -> `yarn add package_name`
* `npm uninstall package_name --save` -> `yarn remove package_name`
* `npm update package_name --save` -> `yarn add package_name --dev`
* `npm install package@latest --save` -> `yarn add package`
* `npm install package --global` -> `yarn global add package`

## What's the same

* `npm init` -> `yarn init`
* `npm link` -> `yarn link`
* `npm outdated` -> `yarn outdated`
* `npm publish` -> `yarn publish`
* `npm run` -> `yarn run`
* `npm cache clean` -> `yarn cache clean`
* `npm login` -> `yarn login`
* `npm test` -> `yarn test`
* `npm install --production` -> `yarn install --production`

# What's yarn has that npm doesn't have

*  `yarn license ls` 
Inspect your dependencies licenses.
*  `yarn licenses generate-disclaimer`
Create your license dependency disclaimer
*  `yarn why package_name`
Details what packages depend on this package.
* `yarn upgrade-interactive`
Selectively upgrade specific package in a simple way
* Emojis
 Yarn has support for emojis :muscle:
