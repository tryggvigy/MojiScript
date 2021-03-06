# MojiScript Express Hello World

App demonstrates how to interop with JavaScript libraries in a MojiScript application. In this case, we are interoping with `express` to create a simple web server that listens on port 3000.

## Install

```bash
# clone repository
git clone https://github.com/joelnet/MojiScript.git

# enter directory
cd MojiScript/examples/express-hello-world

# install dependencies
npm ci
```

## Run

```bash
npm start
```

You should see the output

```
Listening on port 3000.
```

## Code

[index.mjs](index.mjs) - Load dependencies and settings and start the application.

[main.mjs](main.mjs) - Entrypoint of application.

[interop/express.mjs](interop/express.mjs) - `express` JavaScript interop.
