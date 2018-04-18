# yarn optional dependencies pain

* npx verdaccio
* npm config set @kuali:registry http://localhost:4873
* npm adduser --registry http://localhost:4873
* cd support
* yarn publish --registry http://localhost:4873
* cd ../main
* yarn or yarn --ignore-optional
