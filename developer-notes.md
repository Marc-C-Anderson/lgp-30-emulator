# Developer Notes

## Other Notes

* [Read Me](./README.md)
* [Developer Notes](./developer-notes.md)
* [Release Notes](./release-notes.md)

```shell
npm create cloudflare@latest -- lgp-30-emulator
```

```text
> npx
> create-cloudflare lgp-30-emulator


──────────────────────────────────────────────────────────────────────────────────────────────────────────
👋 Welcome to create-cloudflare v2.54.3!
🧡 Let's get started.
📊 Cloudflare collects telemetry about your usage of Create-Cloudflare.

Learn more at: https://github.com/cloudflare/workers-sdk/blob/main/packages/create-cloudflare/telemetry.md
──────────────────────────────────────────────────────────────────────────────────────────────────────────

╭ Create an application with Cloudflare Step 1 of 3
│
├ In which directory do you want to create your application?
│ dir ./lgp-30-emulator
│
├ What would you like to start with?
│ category Hello World example
│
├ Which template would you like to use?
│ type Static site
│
├ Copying template files
│ files copied to project directory
│
├ Updating name in `package.json`
│ updated `package.json`
│
├ Installing dependencies
│ installed via `npm install`
│
╰ Application created

╭ Configuring your application for Cloudflare Step 2 of 3
│
├ Installing wrangler A command line tool for building Cloudflare Workers
│ installed via `npm install wrangler --save-dev`
│
├ Retrieving current workerd compatibility date
│ compatibility date 2025-11-07
│
├ You're in an existing git repository. Do you want to use git for version control?
│ yes git
│
╰ Application configured

╭ Deploy with Cloudflare Step 3 of 3
│
├ Do you want to deploy your application?
│ no deploy via `npm run deploy`
│
╰ Done

────────────────────────────────────────────────────────────
🎉  SUCCESS  Application created successfully!

💻 Continue Developing
Change directories: cd lgp-30-emulator
Start dev server: npm run start
Deploy: npm run deploy

📖 Explore Documentation
https://developers.cloudflare.com/workers

🐛 Report an Issue
https://github.com/cloudflare/workers-sdk/issues/new/choose

💬 Join our Community
https://discord.cloudflare.com
────────────────────────────────────────────────────────────
```

## Install

```shell
npm i
npm ci
```

## Cloudflare Scripts

```shell
npm run cf:dev
npm run cf:build
npm run cf:deploy
```

## Vite Scripts

```shell
npm run vite:dev
npm run vite:build
npm run vite:preview
```
