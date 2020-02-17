# prettier-config-mx

### How to use

If you don't require any further customization, you can utilize your own `package.json`

```
 {
  "name": "my-cool-library",
  "version": "9000.0.1",
  "prettier": "prettier-config-mx"
}
```

If you require customization, you can extend from the shared config by creating a `prettierrc.js` file as such

```
module.exports = {
  ...require("prettier-config-mx"),
  semi: false
};
```
