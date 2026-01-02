# Quickstart

## Create your first site

Getting started with your developer platform is easy. Follow these steps to set up your first site.

### Step 1: Install dependencies

```bash
npm install example-api
```

### Step 2: Initialize the client

```javascript
import ExampleAPI from "example-api";

const client = new ExampleAPI({
  apiKey: process.env.API_KEY
});
```

### Step 3: Make your first request

```javascript
const response = await client.messages.send({
  message: "Hello, world!"
});

console.log(response);
```

## Next steps

* Learn about [Editor basics](../basics/editor.md)
* [Publish your docs](publish-your-docs.md) to share with your team
