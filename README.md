# @meltstudio/prettier-config

Melt Studio's [Prettier](https://prettier.io/) config.

## Usage

1. Install:

   ```bash
   yarn add --dev @meltstudio/prettier-config
   ```

1. Use the configuration

   In your `.prettierrc`:

   ```json
   "@meltstudio/prettier-config"
   ```

   Or in the `package.json`:

   ```json
   {
     ...
     "prettier": "@meltstudio/prettier-config",
     ...
   }
   ```

   Or if you want to override the default configuration:

   ```javascript
   // .prettierrc.js
   module.exports = {
     ...require('@meltstudio/prettier-config'),
     semi: false,
   };
   ```
