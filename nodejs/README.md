# nodejs git cliff configuration

Rolling config url:

```
https://raw.githubusercontent.com/danielpza/git-cliff-config/refs/heads/master/nodejs/cliff.toml
```

Add the following to your `package.json` `scripts` property:

```json
"git-cliff": "git-cliff --config-url https://raw.githubusercontent.com/danielpza/git-cliff-config/refs/heads/master/nodejs/cliff.toml",
```
