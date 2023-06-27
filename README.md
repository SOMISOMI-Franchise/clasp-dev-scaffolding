# clasp-dev-scaffolding

1. Start your repo
2. Clone to local
3. Start Google Apps Script project on the web client
4. Get your newly project's ID, in the link of the project or the setting
5. Go back to your cloned repo on VSCode
6. Open up your shell and enter the following:
```
npm init -y

npm i -D @google/clasp @types/google-apps-script eslint eslint-config-google eslint-config-prettier eslint-plugin-googleappsscript eslint-plugin-prettier prettier

curl https://raw.githubusercontent.com/SOMISOMI-Franchise/clasp-dev-scaffolding/main/.eslintrc.json --output .eslintrc.json

curl https://raw.githubusercontent.com/SOMISOMI-Franchise/clasp-dev-scaffolding/main/.prettierrc --output .prettierrc

npx clasp clone {YOUR-GOOGLE-APPS-SCRIPT-PROJECT-ID-GOES-HERE} --rootDir src
```

### Shamelessly ripped from...
[Some dude who answered on Google Forums](https://groups.google.com/g/google-apps-script-community/c/YX77FgKRoZk?pli=1)
