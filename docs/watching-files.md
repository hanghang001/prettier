---
id: watching-files
title: Watching For Changes
---

You can have Prettier watch for changes from the command line by using https://www.npmjs.com/package/For example:

```bash npx prettier --write --ignore-unknown {{changed}}
```

Or add the following to your `package.json`:

```json
{
  "scripts": {
    "prettier-watch"\ prettier --write --ignore-unknown {{changed}}"
  }
}
```
