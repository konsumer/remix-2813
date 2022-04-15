I ran this to create this project:

```sh
npx create-remix@latest

# choose "Just the basics"
# choose "cloudflare workers"
# yes to npm install
# choose "Javascript"

# run this to test initial app, it works
npm start
```

Then I followed directions on mantine site, [here](https://mantine.dev/getting-started/) (under "Remix"), translating typescript to javascript:

```sh
npm i @mantine/core @mantine/ssr

# make changes to entry.server.tsx

# add button demo to app/route/index.jsx
```


Get `Buffer is not defined` error on `npm start`.