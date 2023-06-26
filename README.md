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

curl https://raw.githubusercontent.com/SOMISOMI-Franchise/clasp-dev-scaffolding/main/.eslintrc.json?token=GHSAT0AAAAAACDRGSHQ5FXSF7UTSVC6M5JAZE2ALGA --output .eslintrc.json

curl https://raw.githubusercontent.com/SOMISOMI-Franchise/clasp-dev-scaffolding/main/.prettierrc?token=GHSAT0AAAAAACDRGSHRHZUPY7FD2GVSZEECZE2AKWA --output .prettierrc

npx clasp clone {YOUR-GOOGLE-APPS-SCRIPT-PROJECT-ID-GOES-HERE} --rootDir src
```

