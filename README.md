### Riyad's VS Code Settings

<samp><b>Common Settings & Extensions accross all projects</b></samp>

[`settings.json`](./CommonSettingsExtensions/settings.json)<br>
[`extensions.json`](./CommonSettingsExtensions/extensions.json)

<samp><b>FrontEnd VanillaJS Projects</b></samp>

[`.vscode/settings.json`](./CommonSettingsExtensions/settings.json)<br>

<samp><b>FrontEnd VanillaTS Projects</b></samp>

[`.vscode/settings.json`](./VanillaJS/settings.json)<br>

<samp><b>FrontEnd Vue Projects</b></samp>

[`.vscode/settings.json`](./Vue/settings.json)<br>

>Create new project with `npm init vue@latest` </br>
>When creating new project enable eslint and prettier </br>
>That will create necessary `.eslintrc.json` file for your </br>

<samp><b>Backend NodeJs Projects</b></samp>

[`.vscode/settings.json`](./NodeJS/settings.json)<br>
[`.eslintrc.json`](./NodeJS/.eslintrc.json)<br>

```
npm install -D eslint prettier
npx install-peerdeps --dev eslint-config-airbnb-base
npm install -D eslint-config-prettier eslint-plugin-prettier
```