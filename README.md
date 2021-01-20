# JSBook is a coding environment CLI

Installing JSBook on your machine will allow you to create local notebooks where
you write markdown documentation, JS and React (JSX) code that's run and previewed
in the browser.

This environment allows you to import modules from npm and these will be
automatically transpiled and bundled in the browser.

When you're done the notebook will be saved and you can later reopen it and pick
things up where you left them.

The project is written in React and Typescript, uses Redux for state management and esbuild for the
in browser transpiling and bundling. Because esbuild is built in Go and made
available in the browser via wasm, the whole process is blazing fast.