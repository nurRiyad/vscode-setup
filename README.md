### Riyad's VS Code Settings

<samp><b>Common Settings & Extensions accross all projects</b></samp>

[`settings.json`](./CommonSettingsExtensions/settings.json)<br>
[`extensions.json`](./CommonSettingsExtensions/extensions.json)

<br>
<samp><b>FrontEnd Vanilla JS/TS Projects</b></samp>

[`.vscode/settings.json`](./Vanilla/settings.json)<br>

> <samp>add "prettier" to the "extends" array in your .eslintrc.* file. Make sure to put it last, so it gets the chance to override other configs</samp>

```
npm init -y
npm i -D prettier
npm init eslint/config
npm install -D eslint-config-prettier
```

<br>
<samp><b>FrontEnd Vue Projects</b></samp>

[`.vscode/settings.json`](./Vue/settings.json)<br>

```
npm init vue@latest
```

<br>
<samp><b>Backend NodeJs Projects</b></samp>

[`.vscode/settings.json`](./NodeJS/settings.json)<br>
[`.eslintrc.json`](./NodeJS/.eslintrc.json)<br>

```
npm init -y
npm install -D eslint prettier
npx install-peerdeps --dev eslint-config-airbnb-base
npm install -D eslint-config-prettier eslint-plugin-prettier
```
