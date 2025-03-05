# svelte-grid

<p>
  <a href="https://www.npmjs.com/package/svelte-grid"><img  src="https://img.shields.io/npm/v/svelte-grid?style=for-the-badge"/></a>

<a href="https://bundlephobia.com/result?p=svelte-grid@1.5.0">
  <img src="https://img.shields.io/bundlephobia/min/svelte-grid?style=for-the-badge"/>
</a>
  
<a href="https://bundlephobia.com/result?p=svelte-grid@1.5.0">
  <img src="https://img.shields.io/bundlephobia/minzip/svelte-grid?style=for-the-badge"/>
</a>

<a href="https://svelte-grid.now.sh/" target="_blank">
	<img src="https://img.shields.io/website?style=for-the-badge&url=https%3A%2F%2Fsvelte-grid.now.sh%2F">
</a>

</p>

![](https://res.cloudinary.com/dmtrk3yns/video/upload/q_auto/v1565455366/ice_video_20190810-202954_fuquxt.gif)

## About

- 100% Svelte (or vanillajs) - no jQuery, no 3rd party dependencies
- Compatible with Sapper (SSR Svelte)
- Draggable widgets
- Resizable widgets
- Static widgets
- Layout can be serialized and restored
- Responsive breakpoints
- Limit the minimum and maximum width / height when resizing
- Provide helper functions
- Custom dragging
- Grid gap
- Soft autoscroll

## Installation

You would also need to include the `.npmrc` in the consuming project, with the appropriate token before you can install this package.

Below is the `.npmrc` code and replace `<token>` with the appropriate token:

```
engine-strict=true
@aocs-org:registry=https://npm.pkg.github.com
//npm.pkg.github.com/:_authToken=<token>
```

**via NPM**

```code
npm i @aocs-org/lib-svelte-grid --save-dev
```

## Publishing

Before trying to publish, you need to install and build the project.

```
npm install
npm run build
```

Next, in this repository's root directory you would also need to create a `.npmrc` file.

Below is the `.npmrc` code and replace `<token>` with the appropriate token:

```
engine-strict=true
@aocs-org:registry=https://npm.pkg.github.com
//npm.pkg.github.com/:_authToken=<token>
```

After creating the `.npmrc` file, you can run the follow command to publish:

```
npm publish
```

> You might need to configure the `package.json` to publish. For example, `version` needs to updated for every subsequent publish.
