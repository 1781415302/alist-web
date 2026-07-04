## Usage

## Fork changes

This fork adds play count support for AList media files:

- Shows play count badges in the web file list, grid view, and file detail view.
- Reports playback when media is opened from the built-in web player or from the context-menu external-player flow.
- Adds the `zh-CN` language pack to the tracked source tree and uses Simplified Chinese as the default bundled language.

The web client expects an AList backend that provides `/api/fs/playcount/report` and `/api/fs/playcount/query`.

Those templates dependencies are maintained via [pnpm](https://pnpm.io) via `pnpm up -Lri`.

This is the reason you see a `pnpm-lock.yaml`. That being said, any package manager will work. This file can be safely be removed once you clone a template.

```bash
$ npm install # or pnpm install or yarn install
```

### Learn more on the [Solid Website](https://solidjs.com) and come chat with us on our [Discord](https://discord.com/invite/solidjs)

## Available Scripts

In the project directory, you can run:

### `npm dev` or `npm start`

Runs the app in the development mode.<br>
Open [http://localhost:5173](http://localhost:5173) to view it in the browser.

The page will reload if you make edits.<br>

### `npm run build`

Builds the app for production to the `dist` folder.<br>
It correctly bundles Solid in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br>
Your app is ready to be deployed!

## Deployment

You can deploy the `dist` folder to any static host provider (netlify, surge, now, etc.)
