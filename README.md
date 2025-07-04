# Prezence AI Documentation

This repository contains the documentation for Prezence AI.

### Development

Install the [Mintlify CLI](https://www.npmjs.com/package/mintlify) to preview the documentation changes locally. To install, use the following command:

```
npm i -g mintlify
```

Run the following command at the root of your documentation (where `docs.json` is) to start the local development server:

```
mintlify dev
```

### Publishing Changes

Changes are deployed to production automatically after pushing to the default branch.

#### Troubleshooting

- `mintlify dev` isn't running - Run `mintlify install` to re-install dependencies.
- Page loads as a 404 - Make sure you are running in a folder with `docs.json`.
