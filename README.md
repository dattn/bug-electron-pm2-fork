# Bug demo repo
## How to test
```
npm install
npm run version
npm run pm2_version
```
`npm run pm2_version` is failing with the error `TypeError: Buffer is not a constructor`
While running it with normal nodejs bin, it is working fine.
```
node .node_modules ./node_modules/pm2/bin/pm2 --version
```
