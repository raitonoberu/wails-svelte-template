# wails-svelte-template

A minimal [Wails](https://wails.io/) template based on [Svelte](https://svelte.dev).

## Usage

```bash
wails init -n myapp -t https://github.com/raitonoberu/wails-svelte-template
```

## Building 

To build this project in debug mode, use `wails build`. For production, use `wails build -production`.
To generate a platform native package, add the `-package` flag.

## Live Development

To run in live development mode, run `wails dev` in the project directory. In another terminal, go into the `frontend` 
directory and run `npm run dev`. Now every change you make to the frontend should hot-reload the UI.