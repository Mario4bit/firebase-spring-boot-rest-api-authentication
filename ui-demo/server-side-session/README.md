# Client Side Session Demo for Spring Boot Firebase Authorization middleware

## How to use

- Rename config.example.js to config.js and replace its content with firebase web sdk configuration that you get from firebase dashboard.
- Rename .env.example to .env and replace its MIDDLEWARE_URL to your middleware URI.
- Note : - Cookies won't work with localhost, try to setup a local dev domain mapping (on \*nix systems /etc/host) to the spring server through a reverse proxy.

```
npm install
npm run dev
# or
yarn
yarn dev
```

- go to http://localhost:3000
- login and click on demo link

## Code is based on : https://github.com/zeit/next.js/tree/canary/examples/with-firebase
