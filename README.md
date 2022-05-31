## I Highly recommend you use TypeScript over JavaScript. It is 100% worth the time to learn

This repo was made from [Geocine's Template](https://github.com/geocine/phaser3-rollup-typescript). Their repo is worth a star! If you want to use typescript and don't want the automated pushes to github pages I highly recommend just using their repo.

[Geocine's Template](https://github.com/geocine/phaser3-rollup-typescript) provided a [Phaser 3](https://github.com/photonstorm/phaser) starter with [TypeScript](https://www.typescriptlang.org/), [Rollup](https://rollupjs.org) with ⚡️ lightning fast HMR through [Vite](https://vitejs.dev/).

I changed a few minor things and added a github workflow that will automatically deploy
the site to a gh-page branch on push. This template also removes TS. Follow the below steps.
If you have trouble check my youtube video here [WIP](https://) or contact me (see bottom of README)

## Creating your own project off the template
1. Go to the [Template Repo](https://github.com/CKillen/phaser-template-js)
2. Click the green button "Use Template"
3. Follow instructions. <b>Repo MUST be kept public for gh-pages to work</b>
5. Clone the created repo and run in project directory
```
yarn install
```
To run the dev server
```
yarn dev
```
## Github pages
You only need to do this once
1. in the vite.config.ts change the base to what I have below, except with your information put in the < > spots.  
```
base: "https://<github-account-name>.github.io/<repo-name>/",
```
2. Push to remote
3. Wait for github action to complete. This may take a couple minutes
    - You can check next to the commits to see what stage the action is in
    - Yellow circle - Running the action
    - Green check - Action successful, give it a minute and it should be on your site
    - Red X - Action failed. If you can't figure it out Message me (see bottom of README) 
4. Go to repo's settings
5. On the left select Pages
6. Under source click the branch dropdown and select gh-pages
7. next to the branch dropdown, click the file dropdown and select /docs
8. Click save and wait a minute

It will show you the site url after going through these steps. It should be the exact same as the base you entered earlier. If it is not, copy it and set base to that url and push the change.

To contact me for help please either start an issue or contact me via discord. After joining [the phaser discord community](https://discord.gg/phaser) you can send a direct message to Hicures#7097.