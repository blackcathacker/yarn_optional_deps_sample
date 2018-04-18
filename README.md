# yarn optional dependencies pain

* npx verdaccio
* npm config set @blackcat:registry http://localhost:4873
* npm adduser --registry http://localhost:4873
* cd support
* yarn publish --registry http://localhost:4873
* cd ../main
* yarn or yarn --ignore-optional

```
~/g/t/y/main git:master ❯❯❯ yarn --ignore-optional                                                                                                                                                                                            ⏎ ✱
yarn install v1.6.0
info No lockfile found.
[1/4] 🔍  Resolving packages...
error Couldn't find package "@blackcat/optional_support@~0.5.0" required by "@blackcat/support@~1.0.0" on the "npm" registry.
info Visit https://yarnpkg.com/en/docs/cli/install for documentation about this command.
~/g/t/y/main git:master ❯❯❯ npm i                                                                                                                                                                                                             ⏎ ✱
npm notice created a lockfile as package-lock.json. You should commit this file.
npm WARN optional SKIPPING OPTIONAL DEPENDENCY: @blackcat/optional_support@~0.5.0 (node_modules/@blackcat/support/node_modules/@blackcat/optional_support):
npm WARN 404 SKIPPING OPTIONAL DEPENDENCY: Not Found: @blackcat/optional_support@~0.5.0
npm WARN @kuail/main@1.0.0 No description
npm WARN @kuail/main@1.0.0 No repository field.

added 1 package in 1.277s
```
