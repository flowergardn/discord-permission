# discord-permission

An easy to use Discord permission calculator.

<p align="center">
  `npm install discord-permission`
</p>

## Usage

```js
const { calculate } = require("discord-permission");

const hasManageServer = calculate(permission, bitfield); // boolean

/* 

examples:

outputs false:
calculate("MANAGE_GUILD", 1071698529857)


outputs true:
calculate("MANAGE_GUILD", 4398046511103)

*/
```

## License

[MIT](https://choosealicense.com/licenses/mit/)
